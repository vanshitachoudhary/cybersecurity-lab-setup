# 🛡️ Cybersecurity Lab Setup - Phase 1

This repository contains the foundational setup for my ethical hacking and cybersecurity practice environment, configured using Oracle VirtualBox.

## 📋 Lab Architecture & Configurations
* **Base Hypervisor:** Oracle VirtualBox (v7+)
* **Network Setup:** Custom NATNetwork (`10.0.0.0/24`) for isolated and secure VM communication.
* **Attacking Machine:** Kali Linux (Static IP: `10.0.0.2/24`).
* **Integration Features:** 
  * Clipboard and Drag-and-Drop enabled.
  * Host Shared Folder (`/downloads`) configured.
* **State Management:** Baseline snapshot saved as `Kali-Week1-Setup`.

## 🚀 Network Topology
- **Subnet:** `10.0.0.0/24`
- **Gateway:** `10.0.0.1`
- **Kali Linux IP:** `10.0.0.2`
