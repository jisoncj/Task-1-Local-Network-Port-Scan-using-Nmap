# Task-1 Local Network Port-Scan using Nmap

## Objective
Learn to discover open ports on devices in a local network to understand network exposure using Nmap.

## Tools Used
Nmap – Network scanner (free, open-source).
Wireshark – Packet analyzer.

## Port Scanning
Port scanning is the process of probing a server or host for open ports. It helps network administrators understand what services are exposed on a network, and helps attackers identify potential entry points.

## Command Used
sudo nmap -sS 192.168.1.0/24
sudo nmap -sS -sV -O 192.168.1.0/24
sudo nmap -sS 192.168.1.0/24 -oN scan_results.txt

## Files Included
scan_results.txt
Screenshots

## Key Concepts Learned

- Open Port: A port that accepts connections
- TCP SYN Scan: Fast and stealthy scanning method
- Network Reconnaissance: Gathering network information
- IP Range: 192.168.1.0/24 network range
- Firewall: Controls access to ports
