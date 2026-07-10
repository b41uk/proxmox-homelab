# Proxmox Installation

This document will describe the installation process of Proxmox VE on the HomeLab host.

## Installation Plan

1. Backup any important data from the machine.
2. Download the Proxmox VE ISO.
3. Create a bootable USB installer.
4. Enable virtualization in BIOS/UEFI.
5. Boot from the USB installer.
6. Install Proxmox VE.
7. Configure a static IP address.
8. Access the web interface.
9. Update the system.
10. Upload ISO images for virtual machines.

## BIOS/UEFI Settings

Pending verification:

- Virtualization: Pending
- Secure Boot: Pending
- Boot order: Pending
- Power settings: Pending

## Network Configuration

| Setting | Value |
|---|---|
| Hostname | pve-homelab |
| IP Address | 192.168.1.50 |
| Gateway | 192.168.1.1 |
| DNS | 192.168.1.1 |
| Web Interface | https://192.168.1.50:8006 |

## Post-Installation Tasks

- Update package repositories.
- Install available updates.
- Configure storage.
- Upload ISO images.
- Create the first test VM.
- Configure backup location.
- Review firewall settings.

## Notes

This section will be updated with screenshots and real installation details once the deployment starts.
