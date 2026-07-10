# Virtual Machines

This document describes the planned virtual machines for the Proxmox HomeLab.

## Planned Virtual Machines

## docker-host

Purpose:

Docker services and containerized applications.

Planned resources:

| Resource | Value |
|---|---|
| CPU | 2 cores |
| RAM | 4 GB |
| Disk | 40 GB |
| OS | Ubuntu Server |

Planned services:

- Docker
- Docker Compose
- Portainer
- Uptime Kuma
- Nginx Proxy Manager

---

## ai-rag-lab

Purpose:

Testing AI and RAG-related services.

Planned resources:

| Resource | Value |
|---|---|
| CPU | 2-4 cores |
| RAM | 6-8 GB |
| Disk | 60 GB |
| OS | Ubuntu Server |

Planned services:

- PostgreSQL
- pgvector
- Embeddings service
- RAG prototype
- Python backend

---

## windows-server-lab

Purpose:

Windows Server administration practice.

Planned resources:

| Resource | Value |
|---|---|
| CPU | 2 cores |
| RAM | 4-8 GB |
| Disk | 60 GB |
| OS | Windows Server |

Planned features:

- Active Directory
- DNS
- Users and groups
- Group Policy Objects

---

## security-lab

Purpose:

Cybersecurity practice in an isolated environment.

Planned resources:

| Resource | Value |
|---|---|
| CPU | 2 cores |
| RAM | 4 GB |
| Disk | 40 GB |
| OS | Kali Linux / Ubuntu |

Planned usage:

- Security tools
- Defensive testing
- Vulnerability analysis
- Hardening practice

## Notes

Resource allocation may change depending on the final hardware.

