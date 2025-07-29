# Home Lab V2: Evolving Infrastructure for a Personal SOC

## 🎯 Project Goal

This repository documents the journey of building and evolving a personal Home Lab. The primary objective is to create a robust and scalable infrastructure for hands-on cybersecurity research, culminating in a fully functional mini-Security Operations Center (SOC) using **Wazuh SIEM on a dedicated Virtual Machine**.

## 🔄 Project Evolution: From TrueNAS to UGREEN + VM

This project has undergone a significant architectural pivot, reflecting real-world engineering trade-offs:

* **V1 (The Custom Build):** The initial phase focused on building a custom NAS with **TrueNAS SCALE** and enterprise-grade **SAS hardware**. This exercise provided deep insights into low-level hardware integration and advanced ZFS storage configuration.
* **V2 (The Streamlined Approach):** The current architecture utilizes a commercial **UGREEN NAS** for stable and efficient storage, while decoupling the security components. The **Wazuh SIEM** is now planned for deployment in a dedicated **Virtual Machine**, allowing for greater flexibility and independent resource management.

This iterative process demonstrates the ability to adapt technical solutions to meet practical requirements.

## 🗺️ Project Roadmap & Status

### Part 1: Network Attached Storage (✅ Completed)
- **Folder:** [`/nas-ugreen-setup`](/nas-ugreen-setup)
- **Objective:** Deploy and configure the UGREEN NAS for centralized and reliable data storage.
- **Status:** The NAS is fully operational.

### Part 2: SIEM Deployment (⏳ In Progress - MVP Target)
- **Folder:** [`/siem-wazuh-vm`](/siem-wazuh-vm)
- **Objective:** Deploy, configure, and manage a Wazuh SIEM instance on a VM to centralize log collection and security monitoring for the entire lab.
- **Current Status:** Planning phase. The immediate goal is to create a Minimum Viable Product (MVP) with the Wazuh server installed and collecting logs from at least one source.

## 🛠️ Tech Stack
- **Storage:** UGREEN NAS
- **Virtualization:** [vmware workstation]
- **SIEM:** Wazuh
- **Initial Hardware Research:** TrueNAS SCALE, SAS Drives
