# Docker Services

This document describes the planned Docker services for the HomeLab.

## Docker Host

The Docker Host will be deployed as a dedicated Ubuntu Server virtual machine.

Its purpose is to run containerized services in an organized and isolated environment.

## Planned Docker Architecture

```text
VM: docker-host
│
├── Docker Engine
├── Docker Compose
│
├── Portainer
├── Uptime Kuma
├── Nginx Proxy Manager
└── Homepage / Dashboard
```

## Planned Services

## Portainer

Purpose:

Web interface for managing Docker containers.

Status:

Planned.

---

## Uptime Kuma

Purpose:

Monitoring internal services and availability.

Status:

Planned.

---

## Nginx Proxy Manager

Purpose:

Reverse proxy for internal web services.

Status:

Planned.

---

## Homepage / Dashboard

Purpose:

Internal dashboard for accessing HomeLab services.

Status:

Planned.

## Docker Goals

- Learn Docker and Docker Compose.
- Deploy useful internal services.
- Practice container management.
- Document configuration and deployment.
- Monitor service availability.
- Understand how containerized infrastructure is managed.

## Future Improvements

- Add Docker Compose files.
- Add screenshots.
- Add backup documentation.
- Add update procedure.
- Add monitoring notes.
- Add service recovery notes.
