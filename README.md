# Wannacry-ransomware-simulation
WannaCry ransomware attack simulation using Kali Linux, Metasploit, and Windows 7 in a controlled lab environment.

## Overview
This project demonstrates a simulated WannaCry ransomware attack in a controlled virtual lab environment for educational and ethical cybersecurity learning purposes. The simulation focuses on vulnerability exploitation, ransomware deployment, reverse shell access, and file encryption using commonly used penetration testing tools.

The project was performed using Kali Linux as the attacker machine and Windows 7 as the victim machine.

---

## Objectives
- Understand how the WannaCry ransomware attack works
- Perform network scanning and vulnerability identification
- Exploit the MS17-010 (EternalBlue) vulnerability
- Gain reverse shell access to the victim machine
- Simulate ransomware deployment and file encryption
- Learn about ransomware propagation and network security risks

---

## Lab Environment

### Attacker Machine
- Kali Linux

### Victim Machine
- Windows 7 (Vulnerable/Unpatched)

### Network Configuration
- NAT Network configured in VirtualBox
- Both virtual machines connected on the same network

---

## Tools Used
- Nmap
- Metasploit Framework
- Kali Linux
- Windows 7
- VirtualBox

---

## Attack Workflow

### 1. Network Scanning
Used Nmap to scan the network and identify vulnerable systems with port 445 open.

### 2. Vulnerability Exploitation
Used the EternalBlue exploit (MS17-010) from Metasploit Framework to exploit the SMB vulnerability on the Windows 7 machine.

### 3. Reverse Shell Access
Successfully gained remote shell access to the target system after exploitation.

### 4. Ransomware Deployment
Uploaded and executed the WannaCry ransomware sample inside the controlled lab environment.

### 5. File Encryption Simulation
Observed ransomware behavior including file encryption and ransom message display.

---

## Key Learnings
- SMB vulnerability exploitation
- Ransomware attack workflow
- Post-exploitation techniques
- Reverse shell handling
- Network scanning and enumeration
- Importance of patch management and network segmentation

---

## Disclaimer
This project was created strictly for educational and ethical cybersecurity learning purposes in a controlled virtual lab environment.

No real systems, networks, or users were targeted. The ransomware sample and exploitation techniques were used only inside an isolated environment for research and learning.

---

## Author
[Shoheb Chauhan]

Cybersecurity Enthusiast | Ethical Hacking | VAPT | Penetration Testing
