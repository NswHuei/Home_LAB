# TrueNASS Homebuild: Budget NAS with SAS Enterprise Drives + LSI IT Mode HBA

## 🎯 Project Goal

This repository documents how to build a high-capacity, budget-friendly home NAS using SAS enterprise drives and an LSI HBA card flashed to IT mode.  
It's aimed at enthusiasts who want to repurpose cheap SAS disks and achieve maximum flexibility at low cost.

## ⚠️ Minimum hardware requirements

- A spare old PC with:
  - At least one gigabit Ethernet port (onboard or PCIe)
  - One free PCIe slot for the HBA card
  - A small SSD or spare HDD for the TrueNAS system drive (a USB stick works for testing, but not recommended for production)
---

## 💡 Why this build?

- ✅ **Low cost:** SAS enterprise drives are often cheap in second-hand markets (eBay, AliExpress, local resellers).
- ✅ **High scalability:** An LSI 9240-8i HBA in IT mode supports up to 8 disks (and more with expanders).
- ✅ **TrueNAS / ZFS friendly:** No hardware RAID interference; full control at the OS level.
- ✅ **Flexible upgrade path:** Add more disks or switch hardware easily.

## Example Build Overview

![Case overview](./images/case_overview.jpg)

![HDD location](./images/hhd_location.jpg)

If you have a spare old PC and some SAS enterprise drives and are wondering how to integrate them into your NAS system, this is one sample solution for you.

First, make sure your case has at least one fan mount to provide cooling for your drives. In this build, I installed 2 SAS disks in the mounting frame, along with a fan to provide airflow over the drives. There is also enough space in the case for proper air intake to keep temperatures low.

