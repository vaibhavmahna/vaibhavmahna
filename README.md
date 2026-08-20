<div align="center">

# 🏛️ Vaibhav Mahna
### **DevSecOps & Cloud Reliability Engineer | Systems Automation, Security & Identity Architect**
📍 *Woodstock, Ontario, Canada 🇨🇦*

<br />

[![Email](https://img.shields.io/badge/Enterprise_Email-vaibhavmahna56%40gmail.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vaibhavmahna56@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect_Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vaibhav-m-8abb96100)
[![GitHub](https://img.shields.io/badge/GitHub-vaibhavmahna-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vaibhavmahna)

<br />

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│  OPERATIONAL SCOPE: Enterprise Infrastructure • Zero-Trust Identity • Fleet Automation │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Red Hat Ansible](https://img.shields.io/badge/Red_Hat_Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Ansible AWX](https://img.shields.io/badge/Ansible_AWX-000000?style=flat-square&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform_IaC-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Linux CIS](https://img.shields.io/badge/Linux_CIS_Hardened-FCC624?style=flat-square&logo=linux&logoColor=black)
![Microsoft Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0089D6?style=flat-square&logo=windows&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

</div>

---

## 📋 Executive Engineering Summary

Senior **DevSecOps and Cloud Reliability Engineer** with extensive experience architecting, hardening, and operating mission-critical hybrid cloud infrastructure. Specialized in building policy-driven identity governance models, centralizing fleet orchestration via Red Hat AWX/Tower, and establishing automated CIS-compliant security baselines.

| Strategic Domain | Engineering Focus & Capabilities |
| :--- | :--- |
| **🔒 Identity & Governance** | Department-wide Privileged Access Management (PAM), Entra ID Conditional Access, automated SSPR infrastructure, and RBAC privilege separation. |
| **⚡ Orchestration & IaC** | Enterprise Ansible AWX Tower control planes, idempotent playbook engineering, modular Terraform IaC templates, and drift remediation. |
| **🛡️ Infrastructure Security** | CIS Level 1 & Level 2 OS hardening, SSH cipher policies, kernel parameter optimization, and automated patch lifecycle pipelines. |
| **☁️ Cloud & Platform Reliability** | Azure Core (VNets, NSGs, Private Endpoints), Blob Storage archival pipelines (SFTP/CFAX/Barracuda), AVD/Citrix performance monitoring. |

---

## 🛠️ Enterprise Architecture & Technical Competencies

### 1. Cloud Infrastructure & Hybrid Network Architecture
* **Microsoft Azure Core Management:** Multi-subscription governance, Management Group hierarchy, Azure Policy enforcement, Resource Group scoping, and enterprise RBAC.
* **Storage Engineering & Tiering:** Azure Blob Storage lifecycle management (Hot, Cool, Cold, Archive), SAS token delegation, Storage Explorer automation, and Private Endpoint isolation.
* **Network Infrastructure:** Azure VNets, Subnets, Network Security Groups (NSGs), Application Security Groups (ASGs), Azure DNS, User-Defined Routing (UDR), and IPAM tooling integration.
* **Virtual Desktop Infrastructure (VDI):** Azure Virtual Desktop (AVD) host pool orchestration, workspace provisioning, application group management, and Citrix Virtual Apps/Desktops infrastructure.

### 2. Configuration Management, Automation & IaC
* **Ansible Control Plane:** Engineering and operational maintenance of dedicated Ansible Control Nodes, dynamic cloud inventories, custom modules, Jinja2 templating, and idempotent execution.
* **Ansible AWX / Red Hat Tower:** Production job templates, multi-phase workflow dispatching, credentials isolation, RBAC delegation, schedule dispatches, and webhook alert integrations.
* **Infrastructure as Code (IaC):** Modular Terraform templates, remote state locking in Azure Storage accounts, CI/CD provisioning pipelines, and automated drift detection.
* **Systems Scripting:** Advanced PowerShell Core/Desktop module development, Python automation (REST API integrations, data transformation), Bash scripting, and Git version control workflows.

### 3. Systems Security, Hardening & Fleet Governance
* **Operating Systems:** Red Hat Enterprise Linux (RHEL 8/9), Ubuntu Server LTS, Debian, Windows Server (2016–2022), and specialized virtual machine workloads.
* **CIS Benchmark Hardening:** Automated enforcement of CIS Level 1 and Level 2 security profiles (PAM configuration, secure SSH ciphers, kernel tuning via `sysctl`, `auditd` logging rules, and service minimization).
* **Automated Patch Lifecycle:** End-to-end patching orchestration via AWX (pre-flight checks, automated VM snapshots, repository sync, staging updates, sequential reboots, daemon health verification, and rollback logic).
* **Identity Infrastructure:** Active Directory Domain Services (AD DS), Group Policy Object (GPO) enforcement, and centralized update management.

### 4. Enterprise Identity, Access & Data Integration
* **Identity & Access Management (IAM):** Microsoft Entra ID (Azure AD), Single Sign-On (SSO), Multi-Factor Authentication (MFA), Conditional Access Policies, and Self-Service Password Reset (SSPR) tooling.
* **Privileged Access Management (PAM):** Fleet-wide Privileged Account rollout, administrative identity separation, least-privilege enforcement, and credential hygiene.
* **Data Integration Pipelines:** Automated SFTP data ingestion routines, CFAX server document-to-blob transformation scripts, and Barracuda archival extraction pipelines.
* **Observability & Analytics:** Azure Monitor, Log Analytics (KQL queries), Citrix Performance Monitoring Dashboards, automated alerting rules, and enterprise SOP wiki governance.

---

## 🏗️ Architecture Initiatives & Technical Case Studies

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                        ENTERPRISE ENGINEERING CASE STUDIES                             │
├───────────────────────────────┬───────────────────────────────┬────────────────────────┤
│ 1. AWX Control Plane          │ 2. CIS Baseline Hardening     │ 3. Automated Patching  │
│ 4. Enterprise PAM Rollout     │ 5. Automated SSPR Architecture│ 6. Azure Data Ingestion│
└───────────────────────────────┴───────────────────────────────┴────────────────────────┘
```

#### ⚙️ Case Study 1: Centralized Automation Control Plane (Ansible AWX Tower)
* **Architecture:** Deployed dedicated Ansible Control Nodes paired with Red Hat AWX Tower to establish a unified enterprise automation control plane.
* **Implementation:** Engineered structured job templates and multi-stage workflow templates handling node provisioning, post-boot bootstrapping, security agent installation, and routine ops maintenance.
* **Operational Impact:** Replaced fragmented manual administration with auditable, RBAC-delegated push-button workflows, reducing server provisioning lead time significantly.

#### 🛡️ Case Study 2: Linux Golden Image Engineering & CIS Hardening
* **Architecture:** Standardized base operating system images (RHEL/Ubuntu) by engineering hardened baseline templates compliant with Center for Internet Security (CIS) benchmarks.
* **Implementation:** Enforced file system partitioning, disabled legacy protocols/kernel modules, configured secure SSH authentication ciphers, and implemented comprehensive audit logging (`auditd`).
* **Operational Impact:** Established a hardened security baseline that passed corporate compliance audits and eliminated configuration drift across newly provisioned workloads.

#### 🔄 Case Study 3: End-to-End Automated Linux OS Patching Workflow
* **Architecture:** Engineered an automated, scheduled patching framework inside Ansible AWX to govern the complete update lifecycle of enterprise Linux servers.
* **Implementation:** Authored playbooks featuring pre-flight health validation, automated VM snapshot generation, package sync, staged reboot sequences, daemon verification, and execution reporting.
* **Operational Impact:** Eliminated weekend manual patching overhead, shortened maintenance windows, and ensured zero-day vulnerability remediation across the server fleet.

#### 🔐 Case Study 4: Enterprise-Wide Privileged Account Management (PAM) Rollout
* **Architecture:** Designed and executed an enterprise-wide Privileged Account Management framework across IT engineering and operations personnel.
* **Implementation:** Decoupled standard user identities from elevated administrative credentials, mandated MFA on privileged accounts, and established strict least-privilege boundaries.
* **Operational Impact:** Mitigated lateral movement vectors and achieved 100% compliance with corporate privilege governance standards.

#### 🔑 Case Study 5: Self-Service Password Reset (SSPR) Tooling Architecture
* **Architecture:** Engineered an end-to-end SSPR solution progressing from Proof-of-Concept (POC) validation to full enterprise rollout.
* **Implementation:** Integrated automated identity verification mechanisms with enterprise directory services to enable secure self-service credential recovery.
* **Operational Impact:** Reduced identity-related support ticket volume by **over 40%**, removing recurring administrative bottlenecks.

#### ☁️ Case Study 6: Enterprise Data Archival & Ingestion Pipelines (Azure Blob)
* **Architecture:** Engineered automated data ingestion pipelines transferring legacy and on-premises archival data into Azure Blob Storage tiers.
* **Implementation:** Built SFTP upload scripts with checksum validation, automated CFAX document-to-blob transformation routines, and Barracuda archival retention extraction.
* **Operational Impact:** Modernized document retention workflows, improved data retrieval SLAs, and optimized long-term cloud storage expenditure.

#### 🌐 Case Study 7: Enterprise IPAM, Citrix Performance Dashboards & Governance
* **Architecture:** Deployed IP Address Management (IPAM) tooling for real-time visibility across hybrid subnet allocations and DNS mappings.
* **Implementation:** Designed Citrix monitoring dashboards tracking session latency, concurrency, and host metrics; authored an internal wiki portal containing SOPs and recovery playbooks.
* **Operational Impact:** Accelerated Tier-2/Tier-3 incident resolution times and eliminated subnet/IP conflict incidents.

---

## 📜 Professional Certifications & Education

```
  CERTIFICATIONS                                EDUCATIONAL BACKGROUND
  ──────────────                                ──────────────────────
  • AZ-700: Azure Network Engineer Associate    • Postgraduate Certificate: Applied Networking
  • AZ-104: Azure Administrator Associate         & System Administration (2018)
  • AZ-140: Azure Virtual Desktop Specialty       Conestoga College, Kitchener, ON, Canada
  • AI-900: Azure AI Fundamentals               • Bachelor of Technology (B.Tech): CS (2016)
  • AZ-900: Azure Fundamentals                    NIEC, IP University, Delhi (Dean's Honors List)
```

---

<div align="center">

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│  AUTOMATING TOIL • HARDENING ENTERPRISE INFRASTRUCTURE • SCALABLE SYSTEMS RELIABILITY │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

</div>
