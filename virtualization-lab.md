# Virtualization Lab Overview

This workstation hosts a multi-OS virtualization lab built using Oracle VirtualBox on Windows 11 Pro. The lab is designed for IT administration practice, system testing, and cybersecurity experimentation in isolated environments.

---

## Host System
- OS: Windows 11 Pro
- Virtualization Platform: Oracle VirtualBox
- Hardware Virtualization: Enabled (Intel VT-x / Nested Paging)

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

### Red Hat Linux
- Name: rhhost1
- OS: Red Hat (64-bit)
- RAM: 4 GB
- CPU: 2 vCPUs
- Network: NAT + Internal Network
- Purpose: Enterprise Linux fundamentals and server concepts

---

### Kali Linux
- Name: kali-linux-2024.3
- OS: Kali Linux (Debian-based)
- RAM: 2 GB
- Network: Bridged Adapter
- Purpose: Cybersecurity tools, security testing labs

---

### Windows Client VMs
- Name: Bonnexandre
- OS: Windows 10 (64-bit)
- Purpose: Windows client environment testing

- Name: Alexis
- OS: Windows 10 (64-bit)
- Purpose: User workstation simulation

---

## Use Cases
- System administration practice
- Virtual networking experiments
- Cybersecurity labs in isolated environments
- Safe testing without impacting host OS
