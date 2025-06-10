<h1 align="center">:computer::spider::closed_lock_with_key:Penetration Testing - Penetration Testing on Metasploitable 2</h1>

<p align="center">
  <a href="https://github.com/omerfaruksekmen"><img src="https://img.shields.io/badge/GitHub-omerfaruksekmen-4c00e6?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"></a>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License Badge">
  <img src="https://img.shields.io/badge/-Kali%20Linux-%23557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux Badge">
</p>

<p align="center">
  This project involves a comprehensive penetration testing scenario targeting a Metasploitable 2 virtual machine using Kali Linux.
  The process includes host discovery with Netdiscover and Nmap, vulnerability scanning with Nessus, and exploitation using the Metasploit Framework.
  Post-exploitation activities such as data extraction via Netcat and traffic monitoring with Wireshark are also performed.
  Key technologies used in the project include VirtualBox, Kali Linux, Metasploitable 2, Metasploit, Nessus, Wireshark, DB Browser for SQLite, Netcat, and Nmap.
</p>

## :camera_flash: Screenshots

### :arrow_down: 1. Installing Virtual Machines
<img src="PenetrationTestingSteps/Screenshot_3.png" width="800"/>

### 📊 2. Metasploitable 2 Login Page and IP Address
<img src="PenetrationTestingSteps/Screenshot_4.png" width="800"/>

### :arrow_down: 3. Nessus Installation
<img src="PenetrationTestingSteps/Screenshot_5.png" width="800"/>

### 🔍 4. Discovery of Devices on the Network
<img src="PenetrationTestingSteps/Screenshot_6.png" width="800"/>

### 📊 5. Port and Service Scanning with Nmap
<img src="PenetrationTestingSteps/Screenshot_7.png" width="800"/>

### 🛡️ 6. Vulnerability Scanning with Nessus
<img src="PenetrationTestingSteps/Screenshot_8.png" width="800"/>

### 🛡️ 6. Nessus - Vulnerability Detail
<img src="PenetrationTestingSteps/Screenshot_9.png" width="800"/>

### 🧠 7. Monitoring Network Traffic With Wireshark
<img src="PenetrationTestingSteps/Screenshot_10.png" width="800"/>

### 💣 8. Metasploit Exploit Usage
<img src="PenetrationTestingSteps/Screenshot_11.png" width="800"/>

### 💣 9. Shell and File Directory Access
<img src="PenetrationTestingSteps/Screenshot_12.png" width="800"/>

### :information_source: 10. Access to FileZilla and Messaging Application Data
<img src="PenetrationTestingSteps/Screenshot_13.png" width="800"/>

### 📁 11. Access to Mozilla Firefox Browser Data
<img src="PenetrationTestingSteps/Screenshot_14.png" width="800"/>

### :information_source: 12. Browser Login and Form data
<img src="PenetrationTestingSteps/Screenshot_15.png" width="800"/>

### :cookie: 13. Browser Cookie Data
<img src="PenetrationTestingSteps/Screenshot_16.png" width="800"/>

## 📈 Conclusion

- Within the scope of this project, vulnerability analysis, exploitation, and network traffic monitoring were successfully performed on a deliberately vulnerable virtual machine such as Metasploitable 2.
Using the Kali Linux environment, it was thoroughly demonstrated how an attacker can infiltrate systems, which vulnerabilities can be exploited, and how such activities can be monitored over the network.
- Through a vulnerability scan using the Nessus tool, the security weaknesses of the services running on the system were identified.
One such vulnerability was found in the “UnrealIRCd” service running on port 6667, which was successfully exploited using the Metasploit Framework.
As a result, a reverse shell session was obtained, granting full control over the target system.
- With the help of Wireshark, both normal network traffic and the data flow during the exploit process were thoroughly analyzed.
It was observed how the attacker connected to the system and which data packets were transmitted at each stage.
This provided valuable hands-on experience in attack detection and forensic analysis.

## :warning: Recommended Security Measures

- System and Software Updates
- Firewall and Port Management
- Vulnerability Scanning
- User Awareness
- Network Traffic Monitoring
- Log Tracking (Log Monitoring)




