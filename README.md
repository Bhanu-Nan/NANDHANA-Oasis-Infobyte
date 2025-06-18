# NANDHANA-Oasis-Infobyte
Completed 4 hands-on cybersecurity tasks during my Security Analyst Internship at Oasis-Infobyte. Includes practical Nmap and Nikto tool usage + research reports on network threats and social engineering. 📍 Tools | 🔎 Research | 💻 Demos | 🛡️ Ethical learning

# 🛡️ Security Analyst Internship Projects - Oasis-Infobyte

Welcome to my Security Analyst Internship portfolio! This repository includes four comprehensive tasks completed as part of my internship. These tasks cover practical cybersecurity skills — from scanning and analyzing vulnerabilities using real-world tools to researching critical threat vectors in the modern cyber landscape.

---

## 📁 Table of Contents
1. 🔍 [Task 1: Network Scanning with Nmap]
2. ⚙️ [Task 2: Web Vulnerability Scanning with Nikto]
3. 📄 [Task 3: Report on Common Network Security Threats]
4. 👥 [Task 4: Report on Social Engineering Attacks]



### 🛡️ Task 1: Basic Network Scanning with Nmap

#### 🎯 Objective:

Perform a basic network scan using **Nmap** to identify open ports and services on a local or virtual machine.

#### 🧰 Tools Used:

* 🛰️ **Nmap** – The Network Mapper

#### 🪜 Steps Performed:

1. **Installed Nmap** on the Kali Linux VM using:

   ```bash
   sudo apt update && sudo apt install nmap
   ```
2. **Identified target machine's IP** using:

   ```bash
   ip a
   ```
3. **Performed version detection scan**:

   ```bash
   nmap -sV <target-ip>
   ```
4. Observed and analyzed open ports and services.

### 📄 Scan Result Snippet

Sample output from the scan:

```
PORT     STATE SERVICE     VERSION
22/tcp   open  ssh         OpenSSH 8.2p1 Ubuntu 4ubuntu0.3
80/tcp   open  http        Apache httpd 2.4.41 ((Ubuntu))
443/tcp  open  https       OpenSSL 1.1.1f
```

---

### 📘 Learnings:

* Understood how to install and use Nmap for port and service detection.
* Learned to analyze common services and interpret scan results.
* Gained experience in basic reconnaissance for penetration testing.

---

 📂 Files Attached:
 ![Screenshot 2025-06-18 174912](https://github.com/user-attachments/assets/9e23863b-7b52-4c71-97cd-62be3c3b43d6)
 ![Screenshot 2025-06-18 175036](https://github.com/user-attachments/assets/1f0ff2e2-0065-42d7-bf34-eaeebeb9217b)
 ![Screenshot 2025-06-18 175149](https://github.com/user-attachments/assets/5488aef2-73b1-4690-ba43-2ad24fd8aa82)
 ![Screenshot 2025-06-18 175214](https://github.com/user-attachments/assets/c8009564-4709-4b0c-b3fc-b89b98199404)





