# Network Reconnaissance with Nmap 🔍

This repository contains results and analysis from a local network scan using Nmap.
It's part of a Cyber Security Internship assignment.

## 🔧 Tools Used
- [Nmap](https://nmap.org/)
- Wireshark (Optional)

## 🧪 What Was Done
- Identified local IP range using `ipconfig` / `ifconfig`
- Scanned using: `nmap -sS 192.168.1.0/24`
- Documented open ports and common services
- Analyzed security implications of the findings

## 📂 Contents
- `nmap_scan_results.txt`: Output from the TCP SYN scan
- `analysis.md`: Breakdown of open ports and associated risks
- `interview_questions.md`: Prepared answers for interview questions
- `wireshark_summary.md`: Insights from Wireshark (optional)
- `screenshots/`: Visuals of terminal or packet capture (optional)

## 🖥️ Terminal_output = 
""" user@kali:~$ nmap -sS 192.168.1.0/24

Starting Nmap 7.93 ( https://nmap.org ) at 2025-05-26 14:22 UTC
Nmap scan report for 192.168.1.1
Host is up (0.0020s latency).
Not shown: 996 closed ports
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  https

Nmap scan report for 192.168.1.105
Host is up (0.0010s latency).
Not shown: 998 closed ports
PORT     STATE SERVICE
139/tcp  open  netbios-ssn
445/tcp  open  microsoft-ds

Nmap done: 256 IP addresses (2 hosts up) scanned in 3.72 seconds """
