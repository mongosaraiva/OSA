

# Debian-Based IT Infrastructure Stack

| Infrastructure Layer | Proposed Solution | Primary Function |
| --- | --- | --- |
| Server Virtualization | Proxmox VE | Virtual machines and LXC containers |
| Storage Infrastructure | TrueNAS | Centralized NAS, SAN and shared storage |
| Firewall & Routing | OPNsense | Network security, firewalling, VPN and routing |
| Network Switching | NVIDIA Cumulus Linux | Data center switching and network fabric |
| Backup & Disaster Recovery | Proxmox Backup Server (PBS) | Backup, deduplication and recovery |
| Central Virtualization Management | Proxmox Datacenter Manager (PDM) | Centralized management of multiple Proxmox environments |
| Monitoring & Observability | Zabbix / Prometheus / Grafana | Infrastructure monitoring, metrics and visualization |
| Configuration Management | Ansible | Infrastructure automation and configuration management |
| Identity & Authentication | FreeIPA | Centralized identity, LDAP, Kerberos and access control |

