# Proxmox HomeLab Infrastructure

Personal virtualization lab designed to practice systems administration, Linux infrastructure, Docker services, cybersecurity and AI/RAG experimentation.

This project documents the planning, deployment and evolution of a HomeLab environment based on Proxmox VE.

## Current Status

> Project planned. Deployment will start soon.

## Objectives

- Build a realistic virtualization lab using Proxmox VE.
- Practice Linux and Windows Server administration.
- Deploy Docker-based services.
- Learn networking, backups and monitoring.
- Create isolated cybersecurity practice environments.
- Experiment with AI and RAG-related services.
- Document the full process as a professional infrastructure project.

## Planned Architecture

```text
Home Network
│
└── Proxmox VE Host
    │
    ├── VM: docker-host
    │   ├── Portainer
    │   ├── Uptime Kuma
    │   └── Nginx Proxy Manager
    │
    ├── VM: ai-rag-lab
    │   ├── PostgreSQL
    │   ├── pgvector
    │   └── AI/RAG experiments
    │
    ├── VM: windows-server-lab
    │   ├── Active Directory
    │   └── DNS
    │
    ├── VM: security-lab
    │   ├── Kali Linux
    │   └── Isolated testing machines
    │
    └── Storage
        ├── ISO images
        ├── VM disks
        └── Backups
```

## Planned Technologies

- Proxmox VE
- Linux
- Ubuntu Server
- Windows Server
- Docker
- LXC Containers
- Networking
- Backups
- Monitoring
- Cybersecurity Labs
- PostgreSQL
- pgvector
- AI/RAG experiments

## Documentation

- docs/01-hardware.md
- docs/02-networking.md
- docs/03-proxmox-installation.md
- docs/04-virtual-machines.md
- docs/05-docker-services.md
- docs/06-backups.md
- docs/07-security.md
- docs/08-ai-rag-lab.md
- docs/09-roadmap.md

## Project Goals

The goal of this HomeLab is not only to deploy services, but to understand how real infrastructure is planned, configured, secured, monitored and documented.

This environment will be used to improve practical skills in:

- Systems administration
- Linux infrastructure
- Virtualization
- Networking
- Cybersecurity
- Automation
- Artificial Intelligence infrastructure
- RAG system experimentation

## Future Improvements

- Add architecture diagrams.
- Add screenshots.
- Add backup strategy documentation.
- Add monitoring dashboards.
- Add security hardening notes.
- Add AI/RAG experiments.
- Add lessons learned.

---

> Building practical infrastructure to learn, break, fix and improve.
