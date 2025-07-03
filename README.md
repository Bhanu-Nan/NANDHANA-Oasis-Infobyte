# NANDHANA-Oasis-Infobyte
Completed 4 hands-on cybersecurity tasks during my Security Analyst Internship at Oasis-Infobyte. Includes practical Nmap and Nikto tool usage + research reports on network threats and social engineering. 📍 Tools | 🔎 Research | 💻 Demos | 🛡️ Ethical learning

# 🛡️ Security Analyst Internship Projects - Oasis-Infobyte

Welcome to my Security Analyst Internship portfolio! This repository includes four comprehensive tasks completed as part of my internship. These tasks cover practical cybersecurity skills — from scanning and analyzing vulnerabilities using real-world tools to researching critical threat vectors in the modern cyber landscape.

---

## 📁 Table of Contents
1. 🔍 [Task 1: Network Scanning with Nmap]
2. ⚙️ [Task 2: Basic Firewall Configuration with UFW]
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


 # 🔥 Task 2 — Basic Firewall Configuration with UFW

 🎯 Goal
- Allow incoming **SSH (port 22)**
- Deny incoming **HTTP (port 80)**
- Display active UFW firewall rules

## 🛠️ Steps Performed

1. Installed UFW using:
   sudo apt update && sudo apt install ufw -y

2. Reset UFW to remove old rules:
   sudo ufw reset

3. Set default policies:
   sudo ufw default deny incoming
   sudo ufw default allow outgoing

4. Allowed SSH (port 22):
   sudo ufw allow 22

5. Denied HTTP (port 80):
   sudo ufw deny 80
 
6. Enabled UFW:
   sudo ufw enable

7. Checked current rules:
   sudo ufw status numbered
✅ Output Summary
Status: active

     To                         Action      From
     --                         ------      ----
[ 1] 22                         ALLOW IN    Anywhere
[ 2] 80                         DENY IN     Anywhere
[ 3] 22 (v6)                    ALLOW IN    Anywhere (v6)
[ 4] 80 (v6)                    DENY IN     Anywhere (v6)
📸 Screenshot
Below is proof that the configuration was successful:


🧠 Notes
SSH (port 22) must be allowed before enabling UFW to prevent lockout.

UFW handles IPv6 rules by default if IPv6 is enabled.






