# Virtualization Lab Overview

This workstation hosts a multi-OS virtualization lab built using Oracle VirtualBox on Windows 11 Pro. The lab is designed for IT administration practice, system testing, and cybersecurity experimentation in isolated environments.

## Role Context
This lab was built to simulate real-world IT environments commonly used in desktop support, system administration, and cybersecurity roles. All systems are isolated to allow safe testing and experimentation.

## Use Cases
- System administration practice
- Virtual networking experiments
- Cybersecurity labs in isolated environments
- Safe testing without impacting the host OS

## What This Demonstrates
- Virtual machine deployment and management
- Multi-OS administration (Windows & Linux)
- Virtual networking configuration (NAT, Bridged, Internal)
- Security-focused lab isolation
- Resource allocation and system stability awareness

---

## Host System
- OS: Windows 11 Pro
- Virtualization Platform: Oracle VirtualBox
- Hardware Virtualization: Enabled (Intel VT-x / Nested Paging)

## Virtualization Lab Overview (Visuals)

### Oracle VirtualBox – VM Overview
![VirtualBox Overview](images/vbox-overview.png)

### Ubuntu Linux VM
![Ubuntu VM Running](images/ubuntu-running.png)

### Kali Linux VM
![Kali Linux VM Running](images/kali-running.png)

### Windows Client VM
![Windows VM Running](images/windows-vm-running.png)

---

## Virtual Machines Inventory

### Ubuntu Linux (Admin VM)
- Name: Alex_ubuntu
- OS: Ubuntu (64-bit)
- RAM: ~4 GB
- Network: Bridged Adapter
- Purpose: Linux administration, services, CLI practice

---

### Ubuntu Linux (Server VM)
- Name: dbhost1
- OS: Ubuntu (64-bit)
- RAM: 2 GB
- Network: NAT + Internal Network
- Purpose: Server / backend host simulation

---

### Red Hat Linux (Enterprise VM)
- Name: rhhost1
- OS: Red Hat (64-bit)
- RAM: 4 GB
- CPU: 2 vCPUs
- Network: NAT + Internal Network
- Purpose: Enterprise Linux fundamentals and server concepts

---

### Kali Linux (Security VM)
- Name: kali-linux-2024.3
- OS: Kali Linux (Debian-based)
- RAM: 2 GB
- Network: Bridged Adapter
- Purpose: Cybersecurity tools and security testing labs

---

### Windows Client VMs
- Name: Bonnexandre
- OS: Windows 10 (64-bit)
- Purpose: Windows client environment testing

- Name: Alexis
- OS: Windows 10 (64-bit)
- Purpose: User workstation simulation

