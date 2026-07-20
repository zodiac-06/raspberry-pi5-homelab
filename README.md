# raspberry-pi5-homelab
A Raspberry Pi 5 homelab featuring Docker, Portainer, Grafana, n8n, and Cloudflare Tunnel with automatic startup and remote access.

# Raspberry Pi 5 Homelab

![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-5-C51A4A?logo=raspberrypi)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker)
![Cloudflare Tunnel](https://img.shields.io/badge/Cloudflare-Tunnel-F38020?logo=cloudflare)
![Grafana](https://img.shields.io/badge/Grafana-Monitoring-F46800?logo=grafana)
![n8n](https://img.shields.io/badge/n8n-Automation-EA4B71)
![Portainer](https://img.shields.io/badge/Portainer-Management-13BEF9)

A self-hosted Raspberry Pi 5 homelab designed for automation, monitoring, and remote management using Docker and Cloudflare Tunnel.

---

# Features

- Raspberry Pi 5 booting from a 500 GB USB HDD
- Docker containerized services
- Portainer for Docker management
- Grafana for monitoring
- n8n automation platform
- Cloudflare Tunnel for secure remote access
- Automatic service startup after reboot
- Systemd service management

---

# Hardware

| Component | Details |
|-----------|---------|
| SBC | Raspberry Pi 5 |
| Storage | 500 GB USB HDD |
| Power | Powered USB Hub |
| OS | Raspberry Pi OS (64-bit) |

---

# Software Stack

| Software | Purpose |
|----------|---------|
| Docker | Container Platform |
| Portainer | Docker Management |
| Grafana | Monitoring Dashboard |
| n8n | Workflow Automation |
| Cloudflare Tunnel | Secure Remote Access |

---

# Architecture

> *(Architecture diagram will be added here.)*

---

# Services

| Service | Description |
|----------|-------------|
| Portainer | Docker container management |
| Grafana | Metrics visualization |
| n8n | Workflow automation |

---

# Installation

Coming soon.

---

# Screenshots

Coming soon.

---

# Troubleshooting

During this project the following issues were encountered and resolved:

- Raspberry Pi USB HDD boot configuration
- Raspberry Pi EEPROM update
- Cloudflared systemd startup timeout
- Portainer initialization timeout
- SSH host key mismatch after storage migration

---

# Future Improvements

- Docker Compose migration
- Prometheus
- Node Exporter
- Uptime Kuma
- Wazuh SIEM
- Automatic backups
- NAS storage partition

---

# License

MIT License
