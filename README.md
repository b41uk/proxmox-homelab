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
