<div align="center">

# 🏛️ Vaibhav Mahna
### **DevSecOps & Cloud Reliability Engineer | Systems Automation, Security & Identity Architect**
📍 *Woodstock, Ontario, Canada 🇨🇦*

<br />

[![Enterprise Email](https://img.shields.io/badge/Email-vaibhavmahna56%40gmail.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vaibhavmahna56@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vaibhav-m-8abb96100)
[![GitHub](https://img.shields.io/badge/GitHub-vaibhavmahna-00C4FF?style=for-the-badge&logo=github&logoColor=black)](https://github.com/vaibhavmahna)

<br />

```yaml
# OPERATIONAL SCOPE & ARCHITECTURAL FOCUS
Cloud_Infrastructure: "Microsoft Azure Core (VNets, NSGs, Storage, AVD/Citrix)"
Automation_Control Plane: "Red Hat AWX / Tower & Ansible Idempotent Fleet Orchestration"
Security_&_Governance: "CIS Level 1 & 2 Hardening | Entra ID | Zero-Trust PAM"
```

<br />

![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Red Hat Ansible](https://img.shields.io/badge/Red_Hat_Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Ansible AWX](https://img.shields.io/badge/Ansible_AWX-000000?style=for-the-badge&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform_IaC-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Linux CIS](https://img.shields.io/badge/Linux_CIS_Hardened-F59E0B?style=for-the-badge&logo=linux&logoColor=black)
![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0284C7?style=for-the-badge&logo=windows&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-0284C7?style=for-the-badge&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-10B981?style=for-the-badge&logo=gnu-bash&logoColor=white)

</div>

---

> [!NOTE]
> ### 👨‍💻 Executive Summary
> Senior **DevSecOps and Cloud Reliability Engineer** specializing in designing, automating, and maintaining mission-critical enterprise systems. Expert in policy-driven security, zero-trust Privileged Access Management (PAM), Red Hat AWX orchestration, and enterprise Azure cloud architectures.

---

## 🛠️ Strategic Capabilities Matrix

| Domain | Focus Area | Technologies & Architecture |
| :--- | :--- | :--- |
| <img src="https://img.shields.io/badge/Azure_Cloud-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white" /> | **Infrastructure & Storage** | VNets, Subnets, NSGs, Private Endpoints, Blob Storage Tiering (Hot/Cool/Archive), SAS Tokens, AVD & Citrix Host Pools |
| <img src="https://img.shields.io/badge/Ansible_AWX-EE0000?style=flat-square&logo=ansible&logoColor=white" /> | **Automation & IaC** | AWX Tower Control Nodes, Workflow Templates, Dynamic Inventories, Terraform Remote State, Idempotent Playbooks |
| <img src="https://img.shields.io/badge/CIS_Security-F59E0B?style=flat-square&logo=shield&logoColor=white" /> | **Hardening & Patching** | CIS Level 1 & Level 2 Baselines (PAM, SSH, sysctl, auditd), Automated AWX Patch Lifecycles, Zero-Day Vulnerability Mitigation |
| <img src="https://img.shields.io/badge/Entra_Identity-0284C7?style=flat-square&logo=windows&logoColor=white" /> | **Identity & Integration** | Entra ID (Azure AD), Conditional Access, PAM Separation, SSPR Tooling, SFTP/CFAX/Barracuda Blob Pipelines, IPAM Tooling |

---

## 🏗️ Architecture Initiatives & Technical Case Studies

> [!IMPORTANT]
> ### ⚙️ 1. Centralized Automation Control Plane (Ansible & AWX Tower)
> * **Design & Implementation:** Architected dedicated Ansible Control Nodes paired with Red Hat AWX Tower to serve as the unified automation hub for enterprise infrastructure.
> * **Workflow Automation:** Built structured job templates and multi-step workflow templates that handle server provisioning, post-boot bootstrapping, security agent deployment, and routine operational maintenance.
> * **Operational Impact:** Replaced disjointed manual scripts with standardized, auditable, and role-delegated push-button operations, drastically reducing provisioning lead time.

> [!TIP]
> ### 🛡️ 2. Linux Golden Image Engineering & CIS Benchmark Hardening
> * **Design & Implementation:** Standardized base Linux operating systems (RHEL/Ubuntu) by engineering hardened baseline templates compliant with Center for Internet Security (CIS) benchmarks.
> * **Hardening Scope:** Enforced strict file system partitioning, disabled legacy protocols and unnecessary kernel modules, configured secure SSH authentication ciphers, and implemented comprehensive audit logging policies (`auditd`).
> * **Operational Impact:** Established a security baseline that passed corporate vulnerability audits and eliminated configuration drift across newly deployed workloads.

> [!NOTE]
> ### 🔄 3. End-to-End Automated Linux OS Patching Workflow
> * **Design & Implementation:** Engineered an automated, scheduled patching framework inside Ansible AWX to manage the lifecycle of enterprise Linux servers.
> * **Pipeline Logic:** Authored intelligent playbooks that perform health checks prior to execution, trigger VM snapshot creation, apply targeted security packages, reboot nodes sequentially, verify service recovery, and send execution reports.
> * **Operational Impact:** Eliminated weekend manual patching overhead, reduced maintenance window duration, and ensured zero-day vulnerability remediation across the entire server fleet.

> [!IMPORTANT]
> ### 🔐 4. Enterprise-Wide Privileged Account Management (PAM) Rollout
> * **Design & Implementation:** Planned and executed the rollout of dedicated Privileged Accounts across all IT engineering and operations personnel.
> * **Governance Model:** Decoupled standard user identities from privileged administrative credentials, enforced strict MFA requirements on elevated accounts, and established least-privilege role boundaries.
> * **Operational Impact:** Significantly mitigated lateral movement risks and established compliance with enterprise security and access audit standards.

> [!TIP]
> ### 🔑 5. Self-Service Password Reset (SSPR) Tooling Architecture
> * **Design & Implementation:** Built and deployed an end-to-end SSPR solution, progressing from initial Proof-of-Concept (POC) validation to full IT/enterprise rollout.
> * **Integration:** Integrated automated identity verification mechanisms with enterprise directory services to empower end users to securely recover credentials independently.
> * **Operational Impact:** Decreased identity-related service desk support ticket volume by **over 40%**, eliminating recurring administrative bottlenecks.

> [!NOTE]
> ### ☁️ 6. Cloud Archival & Data Ingestion Pipelines (Azure Blob Storage)
> * **Design & Implementation:** Engineered automated data pipelines to transfer on-premises and legacy archive data directly into scalable Azure Blob Storage tiers.
> * **Pipelines Built:**
>   * Developed robust **SFTP upload automation** with checksum verification and error-handling routines for scheduled data archival.
>   * Configured **CFAX fax server integrations** with background scripts to convert and upload incoming documents directly into secure Azure Blob containers.
>   * Automated data retention and extraction workflows for **Barracuda archival repositories**.
> * **Operational Impact:** Modernized legacy document retention workflows, improved data retrieval speeds, and lowered long-term storage costs.

> [!IMPORTANT]
> ### 🌐 7. Enterprise IPAM Implementation, Citrix Dashboards & Knowledge Governance
> * **Design & Implementation:** Deployed and configured IP Address Management (IPAM) tooling to maintain real-time visibility and control over hybrid subnet allocations and DNS mappings.
> * **Dashboards & Documentation:** Designed real-time Citrix monitoring dashboards to track user connection latency, session concurrency, and host resources; built a comprehensive internal **Wiki Portal** housing architectural diagrams, standard operating procedures (SOPs), and incident recovery playbooks.
> * **Operational Impact:** Accelerated troubleshooting resolution times for Tier-2/Tier-3 incidents and eliminated IP address conflict incidents across hybrid cloud environments.

---

## 📜 Professional Certifications & Education

```
  ┌─────────────────────────────────────────────────────────────┬─────────────────────────────────────────────────────────┐
  │ 🏅 PROFESSIONAL CERTIFICATIONS                              │ 🎓 EDUCATIONAL BACKGROUND                               │
  ├─────────────────────────────────────────────────────────────┼─────────────────────────────────────────────────────────┤
  │ • AZ-700: Microsoft Azure Network Engineer Associate        │ • Postgraduate Certificate: Applied Networking          │
  │ • AZ-104: Microsoft Azure Administrator Associate           │   and System Administration (2018)                      │
  │ • AZ-140: Microsoft Azure Virtual Desktop Specialty         │   Conestoga College, Kitchener, ON, Canada              │
  │ • AI-900: Microsoft Azure AI Fundamentals                   │ • Bachelor of Technology (B.Tech): Computer Science     │
  │ • AZ-900: Microsoft Azure Fundamentals                      │   NIEC, IP University, Delhi (2016) — Dean's Honors List│
  └─────────────────────────────────────────────────────────────┴─────────────────────────────────────────────────────────┘
```

---

<div align="center">

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│  AUTOMATING TOIL • HARDENING ENTERPRISE INFRASTRUCTURE • SCALABLE SYSTEMS RELIABILITY │
└────────────────────────────────────────────────────────────────────────────────────────┘
```

</div>
