# ☁️ Oracle Cloud Infrastructure (OCI) Overview

Welcome! This is a friendly guide to **Oracle Cloud Infrastructure (OCI)** services, including Networking, Compute, Storage, Security, Pricing, and Regions. 🚀

---

## 🌐 1. OCI Networking Services

### 🔗 Dynamic Routing Gateway (DRG)
- Provides a **private connection** between a VCN and on-premises network.  
- Enables **hybrid cloud deployments**.

### 🛡️ Network Security Group (NSG)
- Controls **traffic flow** between specific resources within a VCN.  
- Offers **granular control** compared to Security Lists.

---

## 🖥️ 2. OCI Compute Services

### ⚙️ Instance Configuration
- Combines **instance shape, base image, and metadata**.  
- Allows **pre-defining settings** for quick deployment.

### 💻 Compute Workload Options
- **OCI Compute (VMs):** Full OS control, legacy apps, Windows workloads.  
- **Managed Nodes (OKE):** Kubernetes control, stateful workloads, GPU workloads.  
- **Virtual Nodes:** Serverless Kubernetes infra, batch jobs, spiky workloads.  
- **Run Containers:** Run containers without Kubernetes, ephemeral workloads, Dev/Test.  
- **OCI Functions:** Serverless, event-driven code execution, simple API implementation.

---

## 💾 3. OCI Storage Services

### 📊 Block Volume Performance Levels
- **Lower Cost**, **Balanced**, **Higher Performance**, **Ultra High Performance**  
- Ultra High Performance is suitable for **extremely high IOPS workloads**.

### 🗄️ Object Storage Tiers
- **Standard:** Frequently accessed data.  
- **Infrequent Access:** Occasionally accessed data.  
- **Archive:** Rarely accessed, long-term storage, **lowest cost**.  
  - Restore time: up to 1 hour ⏳  
  - Minimum storage duration: 90 days 📅

### 🔑 Pre-Authenticated Request (PAR) URLs
- Temporary, **secure access** to specific objects.

---

## 🛡️ 4. OCI Security Services

### 🔒 OCI Security Zones
- Enforce **security best practices** automatically.  
- Restrict **resource creation** based on policies.

### 🗝️ OCI Vault
- Securely stores **encryption keys, secrets, and certificates**.  
- Acts as a **centralized repository** for sensitive data.

### 🕵️ OCI Cloud Guard
- Monitors resources for **security issues**.  
- Components: **Targets, Detectors, Problems**  
- Note: Responders are **not** a Cloud Guard component.

---

## 💰 5. OCI Pricing & Budgeting

### 💵 Pricing Factors
- Number of virtual machines running 🖥️  
- VM instance size (OCPUs, memory) 📏  
- Operating system used 🖱️  
- Data transfer (egress to the internet) 🌐

### 🚫 Factors Not Affecting Cost
- Region used by VM **does not directly impact cost**.

### 📧 Budget Notifications
- Email alerts can be configured when **spending thresholds** are reached.

---

## 🌍 6. OCI Regions & Availability Domains

### 🏢 Region
- Geographically distinct area containing **multiple data centers**.

### 🏛️ Availability Domain (AD)
- Fault-isolated data center within a region.  
- Each AD belongs to a region.

### ⚡ Fault Domains
- Protect against **failures within a single AD**.
