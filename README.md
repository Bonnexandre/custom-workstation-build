# Custom High-Performance Workstation Build & Deployment

![Final Build](images/05-final-build-on.jpg)

## Overview
This project documents the planning, assembly, and validation of a custom high-performance workstation. I treated it like an IT deployment: selecting compatible parts, assembling hardware, managing airflow/cabling, and validating successful POST/BIOS recognition.

## Role Context
This project was completed as an independent IT deployment project and follows best practices used in desktop support and workstation provisioning environments.

## Use Case
Designed for:
- Development environments
- Cybersecurity labs
- Virtualization
- High-performance workloads

## What This Demonstrates
- Hands-on hardware deployment
- Troubleshooting methodology
- Documentation and validation discipline
- Readiness for IT Support / Desktop Support roles

## Goals
- Assemble a custom workstation from individual components
- Ensure thermal efficiency and clean airflow
- Validate POST and hardware detection in BIOS
- Prepare system for OS installation and advanced workloads (dev/labs)

## Skills Demonstrated
- Hardware installation (CPU/RAM/SSD/GPU/PSU/cooling)
- Troubleshooting & validation (POST/BIOS checks)
- Cable management and airflow planning
- Deployment documentation (build log + photos)

## Results
- Successful assembly and stable first boot (POST)
- Components verified in BIOS (CPU/RAM/storage/fans)
- Clean internal cable routing and optimized airflow

## Operating System & Virtualization Setup

### Host Operating System
- Windows 11 Pro installed and activated
- UEFI boot mode enabled
- Secure Boot supported
- System drivers installed and verified
- Windows updates applied

### Virtualization Platform
- Oracle VirtualBox installed on host system
- Hardware virtualization enabled (Intel VT-x / VT-d)
- Multiple virtual machines created for lab and testing purposes

### Virtual Machines (Examples)
- Windows virtual machines for testing and administration
- Linux virtual machines for lab environments
- Isolated environments used for learning, experimentation, and system testing

### Purpose
This setup transforms the workstation into a multi-purpose IT and cybersecurity lab, suitable for:
- System administration practice
- Virtualized testing environments
- Security labs and simulations
- Safe experimentation without impacting the host OS

## Documentation
- [Components List](components.md)
- [Build Log](build-log.md)
- [Validation Checklist](validation.md)
- [Lessons Learned](lessons-learned.md)
- [Virtualization Lab Overview](virtualization-lab.md)

