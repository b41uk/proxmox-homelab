# Security

This document describes the security considerations for the HomeLab.

## Security Goals

- Avoid exposing administrative interfaces directly to the Internet.
- Use strong passwords.
- Keep systems updated.
- Use separate users where possible.
- Practice hardening techniques.
- Monitor important services.
- Document security decisions.

## Proxmox Security Notes

The Proxmox management interface should only be accessible from the local network or through a secure VPN.

The Proxmox web interface should not be exposed directly to the Internet.

## Planned Security Measures

- Strong root password.
- Separate users for administration.
- Two-factor authentication if possible.
- Firewall rules.
- Regular updates.
- Backups before major changes.
- Service monitoring.

## Cybersecurity Lab

The cybersecurity lab will be isolated from important services whenever possible.

Planned use cases:

- Linux hardening
- Vulnerability analysis
- Log review
- Access control practice
- Defensive security testing

## Future Improvements

- Network segmentation.
- VPN access.
- Centralized logging.
- Monitoring dashboard.
- Security checklist.
