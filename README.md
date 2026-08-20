<div align="center">

# Hi, I'm Vaibhav Mahna 👋
### **DevSecOps & Cloud Reliability Engineer | Systems Automation, Security & Identity Architect** 
📍 *Woodstock, Ontario, Canada 🇨🇦*

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=0078D4&center=true&vCenter=true&width=750&lines=DevSecOps+%26+Cloud+Reliability+Engineer;Systems+Automation,+Security+%26+Identity+Architect;Automating+Infrastructure+%7C+Enterprise+Linux+%7C+Azure+%7C+AWX)](https://git.io/typing-svg)

<br />

[![Email](https://img.shields.io/badge/Email-vaibhavmahna56%40gmail.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vaibhavmahna56@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vaibhav-m-8abb96100)
[![GitHub](https://img.shields.io/badge/GitHub-vaibhavmahna-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vaibhavmahna)

<br />

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Ansible](https://img.shields.io/badge/Red_Hat_Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![AWX](https://img.shields.io/badge/Ansible_AWX-000000?style=flat-square&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Linux CIS](https://img.shields.io/badge/Linux_CIS_Hardened-FCC624?style=flat-square&logo=linux&logoColor=black)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0089D6?style=flat-square&logo=windows&logoColor=white)

</div>

---

### 👨‍💻 Executive Engineering Profile

I am a **DevSecOps and Cloud Reliability Engineer** specializing in designing, automating, and maintaining mission-critical enterprise systems. My core engineering focuses on:

* **Policy-Driven Security & Identity Governance:** Eliminating standing administrative privileges via department-wide Privileged Access Management (PAM) rollouts, enforcing Microsoft Entra ID conditional access, building automated Self-Service Password Reset (SSPR) platforms, and hardening OS baselines to strict CIS benchmarks.
* **Orchestration & Operational Automation:** Eliminating manual administrative toil through central Ansible Control Nodes, Red Hat AWX Tower workflows, Terraform Infrastructure as Code (IaC), and end-to-end automated OS patch lifecycle pipelines.
* **Data Integration & Platform Reliability:** Building resilient ingestion pipelines into Microsoft Azure Blob Storage (SFTP, Fax servers, Barracuda data), orchestrating enterprise IPAM systems, and monitoring hybrid workloads across Azure Virtual Desktop (AVD) and Citrix.

---

### 🛠 Comprehensive Tech Stack & Domain Expertise

#### 1. Cloud Platforms, Compute & Storage Architectures
* **Microsoft Azure Core:** Subscription models, Management Groups, Resource Groups, Azure Policy, Role-Based Access Control (RBAC).
* **Storage & Tiering:** Azure Blob Storage (Hot, Cool, Cold, Archive tiers), Lifecycle Management policies, SAS tokens, Private Endpoints, Storage Explorer automation.
* **Networking Infrastructure:** Azure Virtual Networks (VNets), Subnets, Network Security Groups (NSGs), Application Security Groups (ASGs), Azure DNS, User-Defined Routing (UDR), IPAM Tooling.
* **End-User Compute:** Azure Virtual Desktop (AVD) host pools, application groups, workspace provisioning, and Citrix virtual apps/desktops infrastructure.

#### 2. Configuration Management, Orchestration & IaC
* **Ansible Automation:** Architecture and maintenance of dedicated Ansible Control Nodes, dynamic inventories, custom modules, jinja2 templates, and idempotent playbooks.
* **Ansible AWX / Tower:** Job templates, workflow templates, credentials isolation, RBAC delegation, scheduled dispatching, and webhook notifications.
* **Infrastructure as Code (IaC):** Modular Terraform templates, remote state locking in Azure Storage, CI/CD provisioning pipelines, and configuration drift remediation.
* **Scripting & Tooling:** Advanced PowerShell (Core/Desktop scripting, module authoring), Python (automation scripts, data ingestion, REST interaction), Bash, and Git version control.

#### 3. Operating Systems, Security Hardening & Patch Governance
* **Linux Systems:** Red Hat Enterprise Linux (RHEL), Ubuntu Server, Debian, and specialized Linux VM nodes.
* **CIS Benchmark Hardening:** Automated implementation of CIS Level 1 and Level 2 security profiles (filesystem permissions, PAM security, SSH cipher hardening, kernel parameters via sysctl, auditd rules, and service minimization).
* **Automated Patch Lifecycle:** End-to-end patching orchestration via AWX (pre-patch validation, automated snapshotting, package repository sync, staging updates, system reboots, daemon health verification, and rollback logic).
* **Windows Server:** Enterprise Windows Server management, Active Directory Domain Services (AD DS), Group Policy Objects (GPOs), and automated update management.

#### 4. Enterprise Identity, Access & Data Integration
* **Identity & Access Management:** Microsoft Entra ID (Azure AD), Single Sign-On (SSO), Multi-Factor Authentication (MFA), Conditional Access Policies, Self-Service Password Reset (SSPR) tooling.
* **Privileged Access Management (PAM):** Enterprise-wide Privileged Account Rollout, administrative identity separation, least privilege enforcement, and credential hygiene.
* **Data Archival & Integration Pipelines:** Custom SFTP upload scripting, CFAX Server automation for document-to-blob transformation, and Barracuda archival processes.
* **Monitoring & Observability:** Azure Monitor, Log Analytics (KQL queries), Citrix Performance Monitoring Dashboards, alert notification rules, and enterprise Wiki knowledge portals.

---

### 🏗 In-Depth Engineering Initiatives & Architecture Case Studies

#### ⚙️ 1. Centralized Automation Control Plane (Ansible & AWX Tower)
* **Design & Implementation:** Architected and deployed dedicated Ansible Control Nodes paired with Red Hat AWX Tower to serve as the unified automation hub for enterprise infrastructure.
* **Workflow Automation:** Built structured job templates and multi-step workflow templates that handle server provisioning, post-boot bootstrapping, security agent deployment, and routine operational maintenance.
* **Operational Impact:** Replaced disjointed manual scripts with standardized, auditable, and role-delegated push-button operations, drastically reducing provisioning lead time.

#### 🛡️ 2. Linux Golden Image Engineering & CIS Benchmark Hardening
* **Design & Implementation:** Standardized base Linux operating systems (RHEL/Ubuntu) by engineering hardened baseline templates compliant with Center for Internet Security (CIS) benchmarks.
* **Hardening Scope:** Enforced strict file system partitioning, disabled legacy protocols and unnecessary kernel modules, configured secure SSH authentication ciphers, and implemented comprehensive audit logging policies.
* **Operational Impact:** Established a security baseline that passed corporate vulnerability audits and eliminated configuration drift across newly deployed workloads.

#### 🔄 3. End-to-End Automated Linux OS Patching Workflow
* **Design & Implementation:** Engineered an automated, scheduled patching framework inside Ansible AWX to manage the lifecycle of enterprise Linux servers.
* **Pipeline Logic:** Authored intelligent playbooks that perform health checks prior to execution, trigger VM snapshot creation, apply targeted security packages, reboot nodes sequentially, verify service recovery, and send execution reports.
* **Operational Impact:** Eliminated weekend manual patching overhead, reduced maintenance window duration, and ensured zero-day vulnerability remediation across the entire server fleet.

#### 🔐 4. Enterprise-Wide Privileged Account Management (PAM) Rollout
* **Design & Implementation:** Planned and executed the rollout of dedicated Privileged Accounts across all IT engineering and operations personnel.
* **Governance Model:** Decoupled standard user identities from privileged administrative credentials, enforced strict MFA requirements on elevated accounts, and established least-privilege role boundaries.
* **Operational Impact:** Significantly mitigated lateral movement risks and established compliance with enterprise security and access audit standards.

#### 🔑 5. Self-Service Password Reset (SSPR) Tooling Architecture
* **Design & Implementation:** Built and deployed an end-to-end SSPR solution, progressing from initial Proof-of-Concept (POC) validation to full IT/enterprise rollout.
* **Integration:** Integrated automated identity verification mechanisms with enterprise directory services to empower end users to securely recover credentials independently.
* **Operational Impact:** Decreased identity-related service desk support ticket volume by **over 40%**, eliminating recurring administrative bottlenecks.

#### ☁️ 6. Cloud Archival & Data Ingestion Pipelines (Azure Blob Storage)
* **Design & Implementation:** Engineered automated data pipelines to transfer on-premises and legacy archive data directly into scalable Azure Blob Storage tiers.
* **Pipelines Built:**
  * Developed robust **SFTP upload automation** with checksum verification and error-handling routines for scheduled data archival.
  * Configured **CFAX fax server integrations** with background scripts to convert and upload incoming documents directly into secure Azure Blob containers.
  * Automated data retention and extraction workflows for **Barracuda archival repositories**.
* **Operational Impact:** Modernized legacy document retention workflows, improved data retrieval speeds, and lowered long-term storage costs.

#### 🌐 7. Enterprise IPAM Implementation, Citrix Dashboards & Knowledge Governance
* **Design & Implementation:** Deployed and configured IP Address Management (IPAM) tooling to maintain real-time visibility and control over hybrid subnet allocations and DNS mappings.
* **Dashboards & Documentation:** Designed real-time Citrix monitoring dashboards to track user connection latency, session concurrency, and host resources; built a comprehensive internal **Wiki Portal** housing architectural diagrams, standard operating procedures (SOPs), and incident recovery playbooks.
* **Operational Impact:** Accelerated troubleshooting resolution times for Tier-2/Tier-3 incidents and eliminated IP address conflict incidents across hybrid cloud environments.

---

### 📜 Professional Certifications & Education

* 🏅 **Microsoft Certified:** Azure Network Engineer Associate (`AZ-700`)
* 🏅 **Microsoft Certified:** Azure Administrator Associate (`AZ-104`)
* 🏅 **Microsoft Certified:** Azure Virtual Desktop Specialty (`AZ-140`)
* 🏅 **Microsoft Certified:** Azure AI Fundamentals (`AI-900`)
* 🏅 **Microsoft Certified:** Azure Fundamentals (`AZ-900`)
* 🎓 **Postgraduate Certificate:** Applied Networking and System Administration | *Conestoga College, Kitchener, ON, Canada* (2018)
* 🎓 **Bachelor of Technology (B.Tech):** Computer Science | *NIEC, IP University, Delhi* (2016) — *Dean's Honors List*

---

<div align="center">
  <sub>Automating toil • Hardening enterprise infrastructure • Scalable systems reliability</sub>
</div>

