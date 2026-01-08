# 🔍 Network Scanner using Scapy

A fast and simple **multithreaded ARP-based network scanner** written in Python.  
This tool scans a given network range (CIDR) and discovers live devices along with their **IP address, MAC address, and hostname**.


## 🚀 Features

- ARP-based local network scanning
- Multithreaded for faster scanning
- Resolves hostnames using reverse DNS
- Clean and readable output
- Supports CIDR notation (e.g., `192.168.1.0/24`)


## 🛠 Requirements

- Python 3.x
- Scapy
- Root / Administrator privileges (required for ARP)

Install dependencies:

-**pip install scapy**

## ▶️ Usage

Run the script with root privileges:

-**sudo python3 scanner.py**


Enter the network range when prompted:

-Enter network ip address: **192.168.1.0/24**

