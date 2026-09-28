
--

## 🎯 Overview & Objectives
This repository contains a full-depth guide to building a local lab for learning network security, system vulnerability assessment, and OS-level defensive concepts. 

* *Isolation:* Fully disconnected from the internet to prevent unintended external traffic.
* *Reproducibility:* Easily revertible using virtual machine snapshots.
* *Observability:* Internal network monitoring to analyze traffic behavior.

—

## ⚙️ Prerequisites & Requirements
* *RAM:* Minimum 8 GB (16 GB recommended).
* *Storage:* 50 GB free SSD space.
* *Hypervisor:* VirtualBox or VMware Workstation.
* *OS Images:*
  * Attacker Machine (e.g., Kali Linux)
  * Target Machine (e.g., Metasploitable / Windows)
--

## 🛡️ Safety & Snapshot Policy
**TL;DR:** Always create a fresh snapshot after initial installation. If your Virtual Machine breaks or gets compromised during testing, simply restore the clean snapshot!
