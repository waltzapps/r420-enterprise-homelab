# Dell PowerEdge R420 Enterprise Homelab

> Building an enterprise-style homelab to learn virtualization, Windows Server, Linux, Docker, networking, automation, private cloud technologies, and self-hosted AI services.
![Project Status](https://img.shields.io/badge/Status-In%20Progress-blue)
![Proxmox](https://img.shields.io/badge/Proxmox-9.2.2-E57000)
![License](https://img.shields.io/badge/License-MIT-green)
---

## Project Overview

This repository documents my journey of transforming a refurbished Dell PowerEdge R420 into an enterprise-style homelab.

The objective is not only to build a functional server but also to gain practical experience with technologies commonly used in enterprise IT environments.

This repository complements my LinkedIn **"Homelab Journey"** series, providing detailed technical documentation, architecture diagrams, screenshots, and implementation notes.

---

## Enterprise Homelab Platform

<img width="1140" height="637" alt="image" src="https://github.com/user-attachments/assets/800910f5-e75e-4421-8eda-ab8043572069" />

The following architecture represents the current state of the project.

---

## Current Platform Versions

| Component | Version |
|-----------|----------|
| Proxmox VE | 9.2.2 |
| Ubuntu Server | 24.04 LTS |
| Docker Engine | 29.1.3 |
| Portainer CE | 2.39.5 LTS |

---

## Journey Timeline

| Journey | Milestone                                  | Status  |
| ------- | ------------------------------------------ | ------  |
| #1      | Dell R420 Restoration & Proxmox Deployment | ✅      |
| #2      | Ubuntu, Docker & Portainer Platform        | ✅      |
| #3      | Enterprise DNS Platform (Pi-hole)          | ⏳      |

---
## Design Principles

The Enterprise Homelab Project follows several design principles:

- Keep the hypervisor dedicated to virtualization.
- Separate workloads into independent virtual machines.
- Use Docker for lightweight application deployment.
- Build modular infrastructure that can grow over time.
- Document every architectural decision and implementation step.

---

## Project Goals

This homelab is designed to simulate a small enterprise IT environment while developing practical infrastructure and system administration skills.

The project focuses on:

- Building an enterprise virtualization platform
- Learning infrastructure deployment through hands-on practice
- Documenting configurations and troubleshooting steps
- Applying industry best practices
- Creating a professional technical portfolio

---

## Objectives

- Build and manage an enterprise virtualization platform using Proxmox VE
- Deploy Linux and Windows Server workloads
- Learn Docker and containerized applications
- Explore enterprise networking concepts
- Implement monitoring and logging solutions
- Automate infrastructure management
- Build a private cloud environment
- Deploy self-hosted AI and LLM services
- Document the complete learning journey
  
---

## Current Environment

| Component| Status |
|----------|--------|
| Proxmox VE 9.2.2 | ✅ Running |
| Ubuntu Server 24.04.3 LTS | ✅ Running |
| Docker Engine 29.1.3 | ✅  Running |
| Portainer CE 2.39.5 LTS | ✅ Running |
| Windows Server | ⏳ Planned |
| Monitoring | ⏳ Planned |
| Automation | ⏳ Planned |
| Private Cloud | ⏳ Planned |
| Self-hosted AI | ⏳ Planned |

---

## Current Project Status

| Phase | Status |
|--------|--------|
| Dell R420 Restoration | ✅ Completed |
| BIOS Update | ✅ Completed |
| iDRAC Firmware Update | ✅ Completed |
| Proxmox VE Installation | ✅ Completed |
| Ubuntu Server Deployment | ✅ Completed |
| Core Infrastructure Configuration | 🚧 In Progress |
|Docker Engine | ✅ Completed |
|Portainer CE | ✅ Completed |
|Pi-hole | ⏳ Planned |
| Windows Server | ⏳ Planned |
| Active Directory | ⏳ Planned |
| Self-hosted Services | ⏳ Planned |
| Monitoring | ⏳ Planned |
| Automation | ⏳ Planned |
| Private Cloud | ⏳ Planned |
| Self-hosted AI / LLM | ⏳ Planned |

---

## Hardware

| Component | Specification |
|----------|---------------|
| Server | Dell PowerEdge R420 |
| CPU | 2 × Intel Xeon E5-2430L v2 |
| Cores / Threads | 12 Cores / 24 Threads |
| Memory | 56 GB DDR3 ECC |
| Storage | 3 × 300 GB SAS |
| Hypervisor | Proxmox VE 9.2.2 |
| Management | iDRAC 7 Enterprise |

---

## Technology Stack

### Infrastructure
- Dell PowerEdge R420
- Proxmox VE

### Operating Systems
- Ubuntu Server
- Windows Server (Planned)

### Virtualization
- Virtual Machines
- Linux Containers (LXC)

### Containers
- Docker
- Docker Compose
- Portainer

### Networking
- Linux Networking
- Virtual Bridges
- DNS
- DHCP

### Monitoring
- Grafana
- Prometheus

### Automation
- Ansible

### AI
- Ollama
- Open WebUI

---

## Skills Being Developed

### Technical Skills

- Virtualization
- Linux Administration
- Windows Server Administration
- Docker & Containers
- Networking
- Infrastructure Monitoring
- Automation
- Self-hosted AI

### Professional Skills

- Technical Documentation
- Infrastructure Planning
- Troubleshooting
- Problem Solving
- Continuous Learning

---

## Repository Structure

```text
docs/            Technical documentation
diagrams/        Architecture diagrams
screenshots/     Project screenshots
scripts/         Automation scripts
assets/          Images and project resources
```
---

## Learning Journey

This repository documents each stage of the homelab project, including:

- Project objectives
- System configuration
- Architecture diagrams
- Screenshots
- Challenges encountered
- Solutions implemented
- Lessons learned
- Best practices

---

## Roadmap

- [x] Restore Dell PowerEdge R420
- [x] Update BIOS and iDRAC
- [x] Install Proxmox VE
- [x] Deploy Ubuntu Server
- [x] Configure Docker Engine
- [x] Deploy Portainer CE
- [ ] Deploy Pi-hole
- [ ] Deploy Self-hosted Services
- [ ] Install Windows Server
- [ ] Configure Active Directory
- [ ] Implement Monitoring
- [ ] Automate Infrastructure
- [ ] Build Private Cloud
- [ ] Deploy Self-hosted AI / LLM

---
## Follow My Journey

This repository complements my LinkedIn **Homelab Journey** series.

While LinkedIn highlights each milestone, this repository provides the detailed technical documentation, architecture diagrams, configurations, and lessons learned throughout the project.

---
## Screenshots

Current project screenshots include:

- Enterprise Homelab Platform v1.0
  <img width="1668" height="943" alt="Enterprise Homelab Platform V1" src="https://github.com/user-attachments/assets/696a3e88-caf2-4ea8-a1b3-f6c629c976c3" />

- Proxmox VE Dashboard
<img width="1914" height="705" alt="Proxmox Host Summary" src="https://github.com/user-attachments/assets/98e74da5-bafc-42dd-88b6-3e2a10f0799e" />

- Ubuntu Server Virtual Machine
<img width="1912" height="823" alt="Proxmox Ubuntu Server Summary 1" src="https://github.com/user-attachments/assets/337d39c8-a2eb-4422-b562-4d97d456e96f" />

- Portainer Community Edition
<img width="1896" height="894" alt="Portainer Environment" src="https://github.com/user-attachments/assets/d7ff6ea8-14bf-4b27-b575-f48778490d52" />

- Docker Environment Verification
<img width="1499" height="380" alt="Terminal Verification 1" src="https://github.com/user-attachments/assets/667b00d2-c861-43dd-a2e1-2fedf9140e7e" />

Additional screenshots will be added as new services are deployed.


---
## Architecture

Current Architecture

- Enterprise Homelab Platform v1.0

Future architecture diagrams will include:

- Network Topology
- Storage Architecture
- Docker Architecture
- Windows Server Architecture
- Kubernetes Architecture
- AI Infrastructure
---

## License

This project is licensed under the MIT License.
