# NMap-and-scrapy-
# 🔍 Nmap & Scapy Lab Documentation

##  Objectives
This lab demonstrates practical use of **Nmap** and **Scapy** for network discovery, scanning, packet crafting, and protocol analysis.  
The goal is to reinforce cybersecurity fundamentals and document results in a professional format.

---

## Setup
- **Environment:** Linux (Parrot OS / Kali recommended)
- **Tools Installed:**  
  - Nmap v7.93+  
  - Python 3.x with Scapy library (`pip install scapy`)  
- **Network:** Local subnet (192.168.1.0/24 used in examples)

---

##  Nmap Labs

### 1. Host Discovery
```bash
nmap -sn 192.168.1.0/24
Nmap scan report for 192.168.1.5
Host is up (0.0020s latency).
Nmap scan report for 192.168.1.10
Host is up (0.0015s latency).
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  http
cybersecurity-labs/
│
├── README.md
├── nmap/
│   ├── host_discovery.png
│   ├── port_scan.png
│   ├── service_detection.png
│   ├── os_fingerprint.png
│   └── nmap_script.png
│
├── scapy/
│   ├── packet_crafting.py
│   ├── send_packet.png
│   ├── sniffing.png
│   └── protocol_analysis.py
