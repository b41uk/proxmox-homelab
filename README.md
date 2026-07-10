# Proxmox HomeLab Infrastructure

🔗 Part of my [personal portfolio](https://b41uk.github.io/portfol1o/)

Personal virtualization lab designed to practice systems administration, Linux infrastructure, Docker services, cybersecurity and AI/RAG experimentation.

This project documents the planning, deployment and evolution of a HomeLab environment based on Proxmox VE.

## Current Status

> Documentation phase complete. Next step: hardware inventory — see [docs/01-hardware.md](docs/01-hardware.md).

## Objectives

- Build a realistic virtualization lab using Proxmox VE.
- Practice Linux and Windows Server administration.
- Deploy Docker-based services.
- Learn networking, backups and monitoring.
- Create isolated cybersecurity practice environments.
- Experiment with AI and RAG-related services.
- Document the full process as a professional infrastructure project.

The goal isn't only to deploy services, but to understand how real infrastructure is planned, configured, secured, monitored and documented — and to use that process to build practical skills in systems administration, virtualization, networking, cybersecurity, automation, and AI/RAG infrastructure.

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

- [01 · Hardware](docs/01-hardware.md)
- [02 · Networking](docs/02-networking.md)
- [03 · Proxmox Installation](docs/03-proxmox-installation.md)
- [04 · Virtual Machines](docs/04-virtual-machines.md)
- [05 · Docker Services](docs/05-docker-services.md)
- [06 · Backups](docs/06-backups.md)
- [07 · Security](docs/07-security.md)
- [08 · AI/RAG Lab](docs/08-ai-rag-lab.md)
- [09 · Roadmap](docs/09-roadmap.md)

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
