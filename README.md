# Azure Administrator Portfolio (AZ-104)

Hands-on implementation, architecture validation, and configuration artifacts completed alongside James Lee's (CloudLee) **Microsoft Azure Administrator (AZ-104)** curriculum.

---

## 📋 Course Curriculum & Project Matrix

| Module | CloudLee Course Section | Hands-on Demos & Core Concepts Covered | Folder |
| :--- | :--- | :--- | :--- |
| **01** | **Identity & Access Management (IAM)** | Entra ID Tenants & Domains, User/Group Administration, Azure RBAC vs. Entra ID Roles. | [`/01-iam`](./01-iam/) |
| **02** | **Governance & Compliance** | Cost Management & Budgets, Azure Policy assignment & remediation, ARM template deployments. | [`/02-governance-compliance`](./02-governance-compliance/) |
| **03** | **Virtual Networking** | Virtual Networks, Subnets, Public IPs, NAT Gateways, NSGs (Augmented Rules), VNet Peering, Azure DNS Private Zones. | [`/03-virtual-networking`](./03-virtual-networking/) |
| **04** | **Load Balancing & Network Security** | Azure Bastion configuration, Azure Firewall implementation, Azure Load Balancers. | [`/04-network-security-loadbalancing`](./04-network-security-loadbalancing/) |
| **05** | **Azure Storage** | Blob Storage, SAS tokens & Access Keys, RBAC auth, Redundancy/Failover, Azure Files & File Sync, Storage Encryption. | [`/05-azure-storage`](./05-azure-storage/) |
| **06** | **Compute: VMs & Scale Sets** | Virtual Machines, High Availability & Placement Groups, Uniform & Flexible VMSS with Autoscale, Azure Disk Encryption (ADE). | [`/06-compute-vms`](./06-compute-vms/) |
| **07** | **PaaS & Container Hosting** | Azure App Service (Deployments & Deployment Slots), Azure Container Registry (ACR & Tasks), ACI, Azure Container Apps. | [`/07-containers-paas`](./07-containers-paas/) |
| **08** | **Data Protection & Business Continuity** | Azure Backup (Recovery Services Vaults), Azure Site Recovery (ASR for Azure VMs). | [`/08-backup-recovery`](./08-backup-recovery/) |
| **09** | **Monitoring & Troubleshooting** | Azure Monitor, Network Watcher (Connection Troubleshoot & Diagnostics), NSG Flow Logs, Traffic Analytics. | [`/09-monitoring-diagnostics`](./09-monitoring-diagnostics/) |

---

## 📂 Repository Folder Structure

```text
├── README.md                                  <-- Course Overview & Tracker (You are here)
│
├── 01-iam/
│   ├── README.md                              <-- Demos: Users, Groups, Custom RBAC
│   └── notes/
│
├── 02-governance-compliance/
│   ├── README.md                              <-- Demos: Budgets, Azure Policies, ARM Templates
│   └── templates/                             <-- ARM JSON templates used
│
├── 03-virtual-networking/
│   ├── README.md                              <-- Demos: VNets, Peering, NSG Rules, DNS
│   └── diagrams/                              <-- VNet Peering & Subnet diagrams
│
├── 04-network-security-loadbalancing/
│   ├── README.md                              <-- Demos: Azure Bastion, Azure Firewall, Load Balancer
│   └── configs/
│
├── 05-azure-storage/
│   ├── README.md                              <-- Demos: Blob Access, SAS Keys, Azure Files & Sync
│   └── commands/                              <-- AzCopy / Storage CLI commands
│
├── 06-compute-vms/
│   ├── README.md                              <-- Demos: VM Creation, VMSS Autoscale, ADE
│   └── scripts/
│
├── 07-containers-paas/
│   ├── README.md                              <-- Demos: App Service Slots, ACR Tasks, ACI, Container Apps
│   └── app-source/
│
├── 08-backup-recovery/
│   └── README.md                              <-- Demos: Backup Policies, Restore Tests, ASR
│
└── 09-monitoring-diagnostics/
    ├── README.md                              <-- Demos: Network Watcher, Flow Logs, Log Analytics
    └── queries/                               <-- Diagnostic KQL queries
