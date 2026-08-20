# Kubernetes Learning Lab on GCP (LFS250 / LFS258 / CKA / KCNA)

This project contains setup scripts and step-by-step instructions to deploy a 2-node Kubernetes lab on Google Cloud Platform (GCP) tailored for Linux Foundation courses (**LFS250**, **LFS258**) and certifications (**KCNA**, **CKA**).

---

## 🎯 Architecture Overview

- **Cloud Provider**: Google Cloud Platform (GCP)
- **VPC Network**: `k8s-lab-vpc` (Custom Subnet `10.240.0.0/24` in `us-central1` or your preferred zone)
- **Nodes**:
  - `k8s-controlplane` (Ubuntu 22.04 LTS, e2-medium: 2 vCPU, 4GB RAM)
  - `k8s-worker1` (Ubuntu 22.04 LTS, e2-medium: 2 vCPU, 4GB RAM)
- **Container Runtime**: `containerd` with `systemd` cgroup driver
- **Kubernetes Version**: `v1.30`+ (aligned with CKA exam environment)
- **Pod CNI**: Calico or Flannel

---

## 🚀 Step 1: Provision GCP VPC & VMs

You can use the Google Cloud Shell or `gcloud` CLI locally.

### Script: `01-deploy-gcp-infrastructure.sh`

Run the script to create the VPC, firewall rules, and 2 virtual machines:

```bash
chmod +x 01-deploy-gcp-infrastructure.sh
./01-deploy-gcp-infrastructure.sh
```

---

## 🔧 Step 2: Prepare both VMs for Kubernetes

SSH into **both** `k8s-controlplane` and `k8s-worker1` VMs:

```bash
gcloud compute ssh k8s-controlplane --zone=us-central1-a
```

Upload or copy `02-k8s-node-prep.sh` to both VMs and execute:

```bash
chmod +x 02-k8s-node-prep.sh
sudo ./02-k8s-node-prep.sh
```

What this script handles:
1. Disables swap & configures kernel module loading (`overlay`, `br_netfilter`)
2. Configures `sysctl` for IP forwarding and bridge traffic filtering
3. Installs and configures `containerd` runtime (`SystemdCgroup = true`)
4. Adds Kubernetes v1.30 official APT repo and installs `kubelet`, `kubeadm`, `kubectl`

---

## ☸️ Step 3: Initialize Control Plane & Join Worker

### On `k8s-controlplane`:

```bash
sudo kubeadm init --pod-network-cidr=192.168.0.0/16 --apiserver-advertise-address=$(hostname -I | awk '{print $1}')
```

Set up `kubectl` access for non-root user:
```bash
mkdir -p $HOME/.kube
sudo cp -i /etc/kubernetes/admin.conf $HOME/.kube/config
sudo chown $(id -u):$(id -g) $HOME/.kube/config
```

Install Calico CNI plugin:
```bash
kubectl apply -f https://raw.githubusercontent.com/projectcalico/calico/v3.28.0/manifests/calico.yaml
```

### On `k8s-worker1`:

Run the `kubeadm join` command output from the `kubeadm init` step above (with sudo).

### Verify Cluster Status:

```bash
kubectl get nodes -o wide
```

---

## 🎓 Recommended Course Roadmap (Linux Foundation)

1. **LFS250 & KCNA**: Learn cloud-native concepts, architecture, container fundamentals, and basic K8s objects (Pods, Deployments, Services).
2. **LFS258 & CKA**: Hands-on administration:
   - Cluster Architecture, Installation & Configuration (`kubeadm`, upgrade procedures)
   - Workloads & Scheduling (Deployments, DaemonSets, StatefulSets, Affinity/Taints)
   - Services & Networking (ClusterIP, NodePort, Ingress, NetworkPolicies)
   - Storage (PV, PVC, StorageClass)
   - Troubleshooting & Maintenance (Cluster backup/restore with `etcdctl`, node drain, logs, metrics)
