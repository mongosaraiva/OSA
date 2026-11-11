
# Open-Source Infrastructure Stack

This infrastructure stack is designed for a self-hosted private data center and is built on open-source software. It is centered on Debian GNU/Linux, and most of its platform components are Debian-based. The exception are;
- OPNsense, runs on FreeBSD.
  

| Infrastructure Layer | Proposed Solution | Primary Function |
| --- | --- | --- |
| Server Virtualization | Proxmox VE | Virtual machines and LXC containers |
| Storage Infrastructure | TrueNAS | Central NAS, SAN and shared storage |
| Firewall & Routing | OPNsense | Network security, firewall, VPN and routing |
| Network Switching | NVIDIA Cumulus Linux | Data center switching and network fabric |
| Backup & Disaster Recovery | Proxmox Backup Server (PBS) | Backup, deduplication and recovery |
| Central Virtualization Management | Proxmox Datacenter Manager (PDM) | Manages several Proxmox environments from one place |
| Server Operating System | Debian GNU/Linux | Open-source operating system for servers and workstations |
| Database | PostgreSQL / MariaDB | Relational database shared by the business apps |
| Configuration Management | Ansible | Infrastructure automation and configuration management |
| Source Control & CI/CD | GitLab | Git repositories, CI/CD pipelines and container registry |
| Secrets Management & PKI | OpenBao | Stores and controls access to secrets, credentials and encryption keys; internal certificate authority |
| Monitoring & Observability | Zabbix / Prometheus / Grafana | Infrastructure monitoring, metrics and dashboards |
| Security Monitoring (SIEM / XDR) | Wazuh | Threat detection, log analysis, file integrity monitoring, vulnerability detection and compliance |
| Identity & Authentication | Samba AD DC + Keycloak | Central directory (LDAP/Kerberos/DNS, AD-compatible) with SSO, OIDC/SAML and MFA |
| Collaboration & File Sharing | Nextcloud | File sync and sharing, calendar, contacts and office documents |
| ERP & Business Applications | Odoo | ERP, CRM, accounting, inventory and HR |
| Telephony / VoIP | FreePBX | IP phone system (Asterisk-based) |
