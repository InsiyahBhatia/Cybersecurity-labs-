# Cybersecurity & Digital Forensics Lab Repository

A consolidated collection of cybersecurity, digital forensics, OSINT, network analysis, and penetration testing laboratory experiments performed in a controlled virtual environment using industry-standard tools on Kali Linux.

This repository demonstrates practical exposure to:

- Digital Forensics
- Memory Analysis
- Network Traffic Investigation
- Open Source Intelligence (OSINT)
- Vulnerability Assessment
- Exploitation Basics
- Password Cracking
- Evidence Recovery

---

# Complete Lab & Assignment Index

| # | Title | Tools / Topics Used |
|---|---|---|
| 01 | [Static & Live Data Acquisition](./Lab-01-Data-Acquisition/) | FTK Imager, dd, LiME |
| 02 | [RAM Analysis using Volatility](./Lab-02-RAM-Analysis/) | Volatility 3, Kali Linux |
| 03 | [Study of Digital Forensics Tools](./Lab-03-Forensics-Tools/) | Autopsy, Wireshark, Volatility, John, Foremost |
| 04 | [Information Gathering using Dmitry](./Lab-04-Information-Gathering/) | Dmitry |
| 05 | [Computer Forensics using Autopsy](./Lab-05-Autopsy/) | Autopsy, Sleuth Kit |
| 06 | [Network Analysis using Wireshark & TCPDump](./Lab-06-Network-Analysis/) | Wireshark, tcpdump, tshark |
| 07 | [Packet Sniffing using Ettercap & Wireshark](./Lab-07-Packet-Sniffing/) | Ettercap, Wireshark, tshark |
| 08 | [Hashing & Data Carving](./Lab-08-Hashing-Data-Carving/) | Hashdeep, Bulk Extractor |
| 09 | [Recovering Evidence using Foremost](./Lab-09-Evidence-Recovery/) | Foremost, ExifTool |
| 10 | [Password Cracking using John the Ripper](./Lab-10-Password-Cracking/) | John the Ripper, Ophcrack |
| A1 | [Google Dorks & Shodan OSINT](./Lab-A1-Google-Dorks-Shodan/) | Google Dorks, Shodan, OSINT |
| A2 | [Nmap on Kali & Metasploitable](./Lab-A2-Nmap-Kali-Metasploitable/) | Nmap, Kali Linux, Metasploitable 2 |
| A3 | [CVE Exploration & Metasploit](./Lab-A3-CVE-Metasploit-Nmap/) | CVE Research, Metasploit, Nmap |

---

# Lab Environment

| Component | Details |
|---|---|
| Operating System | Kali Linux (VM / Native Installation) |
| Target Machines | Metasploitable 2, Local Test Machines |
| Network Setup | NAT / Host-Only Adapter |
| Platforms | VirtualBox / VMware |
| Tools Used | Autopsy, Volatility, Wireshark, Metasploit, Nmap, John the Ripper, Foremost, Hashdeep, Dmitry, Ettercap |

---

# Core Concepts Covered

## Digital Forensics

- Static and live evidence acquisition
- Bit-by-bit disk imaging
- File system analysis
- Deleted file recovery
- Timeline and metadata analysis
- Artifact extraction and investigation

## Memory Forensics

- RAM acquisition and analysis
- Process enumeration
- Active network connection analysis
- Bash history extraction
- Malware/process investigation using Volatility

## Network Forensics

- Packet capturing and inspection
- Protocol filtering
- Traffic analysis using Wireshark
- TCPDump command-line packet analysis
- ARP poisoning and packet sniffing concepts

## Cryptography & Integrity Verification

- MD5/SHA hash generation
- Integrity verification
- Baseline auditing using Hashdeep
- Data carving techniques

## Password & Authentication Forensics

- Dictionary attacks
- Password hash cracking
- ZIP/archive password recovery
- Authentication security analysis

## OSINT & Reconnaissance

- Google Dorking
- Shodan reconnaissance
- Passive information gathering
- Service and exposed asset discovery

## Vulnerability Assessment & Exploitation

- Port and service enumeration with Nmap
- CVE research and vulnerability mapping
- Metasploit Framework basics
- Exploitation workflow using `msfconsole`

---

# Documentation

Each lab contains:

- Objectives
- Theory and concepts
- Commands used
- Step-by-step procedure
- Screenshots
- Observations
- Result / Conclusion

---

# Ethical Use Disclaimer

All experiments and demonstrations in this repository were conducted in isolated virtual machine environments strictly for educational and research purposes.

Unauthorized scanning, exploitation, packet sniffing, or access to systems without permission is illegal and unethical.

---

# Skills Demonstrated

- Digital Forensics
- Cybersecurity Fundamentals
- Memory Analysis
- Network Traffic Analysis
- Vulnerability Assessment
- Penetration Testing Basics
- Linux Command Line
- Incident Investigation
- Security Tool Handling
- Documentation & Reporting

---