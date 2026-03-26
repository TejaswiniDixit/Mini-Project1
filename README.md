# Mini-Project1
# Linux Host-Based Firewall

This project implements a **host-based firewall on Linux** using **Netfilter and iptables**.
The firewall enforces a default deny policy, allows essential services, logs dropped packets,
and ensures persistence across system reboots using systemd.

## Features
- Default deny incoming traffic
- Stateful packet inspection
- SSH access control
- ICMP rate limiting
- Packet logging
- Persistent firewall rules
- Rule automation using Python

## Tools Used
- Linux
- Netfilter
- iptables
- Bash
- Python
- systemd

## Project Type
Group Project (Cybersecurity)

## How to Run
```bash
sudo ./scripts/firewall.sh
