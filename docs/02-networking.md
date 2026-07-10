# Networking

This document describes the planned network configuration for the HomeLab.

## Initial Network Design

The first version of the HomeLab will use a simple flat network.

```text
Router
│
├── Personal devices
│
└── Proxmox VE Host
    ├── VM: docker-host
    ├── VM: ai-rag-lab
    ├── VM: windows-server-lab
    └── VM: security-lab
```

## Planned IP Addressing

| Device / Service | IP Address | Purpose |
|---|---|---|
| Router | 192.168.1.1 | Default gateway |
| Proxmox Host | 192.168.1.50 | Virtualization host |
| Docker Host | 192.168.1.60 | Docker services |
| AI/RAG Lab | 192.168.1.70 | AI experiments |
| Windows Server Lab | 192.168.1.80 | Windows Server practice |
| Security Lab | 192.168.1.90 | Cybersecurity lab |

## Network Goals

- Use static IP addresses for important services.
- Keep the Proxmox management interface accessible only from the local network.
- Avoid exposing administrative panels directly to the Internet.
- Document all internal services and their purpose.
- Keep the first version simple before adding more advanced networking.

## Security Notes

The Proxmox web interface should not be exposed directly to the Internet.

Remote access, if needed in the future, should be done through a secure method such as a VPN.

## Future Improvements

- VLAN segmentation.
- Dedicated management network.
- Firewall rules.
- VPN access.
- Internal DNS naming.
- Network monitoring.
