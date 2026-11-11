

# Debian-Based IT Infrastructure Stack

| Infrastructure Layer | Proposed Solution | Primary Function |
| --- | --- | --- |
| Server Virtualization | Proxmox VE | Virtual machines and LXC containers |
| Storage Infrastructure | TrueNAS | Central NAS, SAN and shared storage |
| Firewall & Routing | OPNsense | Network security, firewall, VPN and routing |
| Network Switching | NVIDIA Cumulus Linux | Data center switching and network fabric |
| Backup & Disaster Recovery | Proxmox Backup Server (PBS) | Backup, deduplication and recovery |
| Central Virtualization Management | Proxmox Datacenter Manager (PDM) | Manages several Proxmox environments from one place |
| Database | PostgreSQL | Relational database shared by the business apps |
| Monitoring & Observability | Zabbix / Prometheus / Grafana | Infrastructure monitoring, metrics and dashboards |
| Configuration Management | Ansible | Infrastructure automation and configuration management |
| Source Control & CI/CD | GitLab | Git repositories, CI/CD pipelines and container registry |
| Identity & Authentication | FreeIPA | Central identity, LDAP, Kerberos, DNS and an internal certificate authority |
| Collaboration & File Sharing | Nextcloud | File sync and sharing, calendar, contacts and office documents |
| ERP & Business Applications | Odoo | ERP, CRM, accounting, inventory and HR |
| Telephony / VoIP | FreePBX | IP phone system (Asterisk-based) |

