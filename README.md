# network-scanning-with-nmap
This project documents practical network enumeration and service discovery using Nmap as part of hands-on cybersecurity training completed through THM. 
## Objectives
- Identify active systems on a network
- Discover open TCP ports
- Detect running services and versions
- Perform basic operating system detection
- Understand network reconnaissance techniques

---

## Tools Used
- Nmap
- Kali Linux
- TryHackMe Lab Environment

---

## Scans Performed

### TCP SYN Scan
```bash
nmap -sS <target-ip>
