# Home Lab: Personal Infrastructure & Security Operations Center (SOC)

## 🎯 Project Goal

This repository documents the journey of building a personal Home Lab from the ground up. The primary objective is to create a robust and scalable infrastructure for hands-on cybersecurity research, culminating in a fully functional mini-Security Operations Center (SOC) using Wazuh SIEM.

## 🗺️ Project Roadmap & Status

This project is divided into several key phases:

### Phase 1: Hardware & NAS Setup (✅ Completed)
- **Folder:** [`/01-Hardware-Setup`](/01-Hardware-Setup)
- **Objective:** Build a cost-effective Network Attached Storage (NAS) server using enterprise-grade hardware.
- **Key Achievements:**
  - Successfully integrated SAS drives in a standard home-use PC build.
  - Deployed and configured **TrueNAS SCALE** for advanced ZFS storage management.

### Phase 2: SIEM Deployment (⏳ In Progress)
- **Folder:** [`/02-SIEM-Deployment`](/02-SIEM-Deployment)
- **Objective:** Deploy, configure, and manage a Wazuh SIEM instance to centralize log collection and security monitoring for the entire lab.
- **Current Steps:**
  - Planning the deployment of Wazuh server (likely in a Docker container on TrueNAS).
  - Researching agent deployment on various lab machines.

### Phase 3: Log Collection & Analysis (🔜 Up Next)
- **Objective:** Forward logs from various sources (e.g., routers, other VMs, applications) to Wazuh and create custom detection rules and dashboards.

## 🛠️ Tech Stack
- **Hardware:** Enterprise SAS Drives, Custom PC Build
- **Operating System:** TrueNAS SCALE
- **Virtualization/Containers:** Docker
- **SIEM:** Wazuh (Planned)
