# 🔍 My First Cybersecurity Lab - Nmap Port Scanning

## 👋 About Me
I'm learning cybersecurity and this is my first hands-on lab using Nmap to scan ports and identify vulnerabilities.

## 🎯 Lab Objectives
1. Learn how to use Nmap port scanner
2. Understand the difference between TCP and UDP ports
3. Identify open ports on my system
4. Learn about security risks of open ports

## 🛠️ Tools Used
- **VirtualBox** with CSE-LABVM
- **Nmap** (Network Mapper) version 7.80
- **Terminal/Command Line**

## 📅 Timeline
- **Start Date:** Jan 7, 2026
- **Last Updated:** Jan 8, 2026

## 📂 Contents of This Repository
1. `my-scans.txt` - Raw scan results from Nmap
2. `what-i-learned.txt` - My notes and key takeaways
3. `README.md` - This file (overview of the project)

## 🚀 How to Run These Scans Yourself

### Prerequisites:
1. Install VirtualBox
2. Download CSE-LABVM
3. Start the VM and open Terminal

### Basic Commands:
```bash
# Scan your own computer
`nmap localhost`

# Scan with version detection
'nmap -sV localhost'

# Scan a practice website (legal!)
'nmap -sV scanme.nmap.org'
