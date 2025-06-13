---
title: "Daina Muiruri | Portfolio"
layout: default
---

<p align="center">
  <img src="/assets/images/photo.jpg" alt="Daina Muiruri" width="180">
</p>


# **Daina Muiruri**  
**ICT Support Specialist | Web Developer | Security Analyst Enthusiast**

---

## 📄 Resume

### 🎓 Academic Background
**BSc Information Technology** – Taita Taveta University (2018 – 2023)  
*Second Class Honors (Upper Division)*

---

### 💼 Work Experience

**ICT Support Specialist** – SLIP Limited (May 2024 – Feb 2025)  
- Trained 50+ users across 10+ companies  
- Led troubleshooting, ticket resolution, and feature onboarding  
- Analyzed logs, escalated issues, and maintained support SLAs

**ERP Consultant** – Softiq Technologies (Mar 2024 – May 2024)  
- Implemented and supported ERP systems  
- Conducted user training and managed technical support

**Intern (ICT)** – Voi Library (Apr 2022 – Jun 2022)  
- Conducted stock taking, configured systems, supported users  
- Installed NVDA for visually impaired users

**Data Validation Clerk** – AC Nielsen (Jun 2019 – Jul 2019)  
- Handled market research data for brands like Coca-Cola, P&G

---

### 🏆 Certifications
- Cybersecurity Fundamentals – IBM
- Introduction to Cyber Security – Cisco
- Cyber Awareness – HP Life
- Information System Auditing & Assurance

---

### 🛠️ Skills

**Technical:**  
HTML, CSS, JavaScript, Python, Django, Git/GitHub, Odoo, Microsoft Dynamics, ERP, Office 365

**Soft Skills:**  
Analytical Thinking, Teamwork, Communication, Project Management, Time Management

---

## 💻 Projects

### 1. **Online Shopping Management System (OSMS)**
A complete e-commerce platform with user registration, product browsing, payments, and admin support.  
**Tech:** Python, Django, MySQL  
**GitHub:** [Project Link](https://github.com/DAINAWAMBUI)

---

---

## 🧪 Lab Challenges

### 🔐 HTB - ACADEMY-GETSTART-SKILLS
- **Problem:** Exploit a vulnerable box via weak credentials  
- **Approach:** Used Nmap, then brute-forced login with Hydra  
- **Tools:** Nmap, Hydra, Firefox  
- **Lessons:** Enumeration is crucial. Weak creds = easy access  
![Screenshot](images/getstart.png)

---

### 🪟 HTB - Windows Fundamentals

**Platform:** Hack The Box Academy  
**Challenge:** Windows Fundamentals Module  
**Link:** [Completed Module Certificate](https://academy.hackthebox.com/achievement/1918160/49)

---

### 🧩 Problem Statement

This lab aimed to reinforce best practices in securing, managing, and auditing Windows systems via command-line tools. Tasks included identifying system build information, locating non-standard files, inspecting user permissions, and managing shared resources and services.

---

### 🛠️ Approach & Tools Used

- ✅ **System Info**: Used `Get-WmiObject` and `Get-CimInstance` to retrieve the **build number** and **Windows version**
- 📁 **Directory Enumeration**: Used `Get-ChildItem` to scan the C:\ drive for **non-standard directories**
- 🔐 **Permissions Check**: Employed `icacls` to determine which users had **full control** over directories like `C:\Users`
- 🌐 **Network Protocols**: Referred to training notes to identify **SMB (Server Message Block)** as the network file-sharing protocol
- 📊 **System Logs**: Confirmed **Event Viewer** as the default log viewer utility
- 📂 **Shared Directory**: Created and managed a shared folder called **Company Data**
- 🧪 **Service Auditing**: Used `Get-WmiObject Win32_Service` to identify **non-standard services**
- 🧾 **Aliases**: Discovered the alias for `ipconfig.exe` was `ifconfig`
- 🔒 **Execution Policy**: Checked using `Get-ExecutionPolicy –List`
- 🔐 **User Management**: Used `wmic` and `New-LocalUser` to identify SIDs for custom users and security groups

---

### 🧪 Key Commands Used

```powershell
Get-WmiObject –Class win32_OperatingSystem | select Version, BuildNumber
(Get-CimInstance Win32_OperatingSystem).Caption
Get-ChildItem -Path C:\ -Directory
icacls C:\Users
Get-Alias | Where-Object { $_.Definition -like "*ipconfig*" }
Get-ExecutionPolicy –List
wmic useraccount get name,sid
New-LocalUser -Name "Jim" –NoPassword
(Get-LocalUser -Name "Jim").SID.Value

![Screenshot](assets/images/windows-fundamentals.png)

---

---

### 💻 HTB - Linux Fundamentals
- **Problem:** Windows file/user misconfigurations  
- **Approach:** Used cmd/PowerShell to explore and identify weaknesses  
- **Tools:** whoami, ipconfig, net user  
- **Lessons:** Learned user privilege basics and common mistakes  
![Screenshot](images/windowsfund.png)

---

---

### 💻 HTB - Introduction to web application
- **Problem:** Windows file/user misconfigurations  
- **Approach:** Used cmd/PowerShell to explore and identify weaknesses  
- **Tools:** whoami, ipconfig, net user  
- **Lessons:** Learned user privilege basics and common mistakes  
![Screenshot](images/windowsfund.png)

---

---

### 💻 HTB - Introduction to Cybersecurity
- **Problem:** Windows file/user misconfigurations  
- **Approach:** Used cmd/PowerShell to explore and identify weaknesses  
- **Tools:** whoami, ipconfig, net user  
- **Lessons:** Learned user privilege basics and common mistakes  
![Screenshot](images/windowsfund.png)

---

---

### 💻 HTB - Getting Started
- **Problem:** Windows file/user misconfigurations  
- **Approach:** Used cmd/PowerShell to explore and identify weaknesses  
- **Tools:** whoami, ipconfig, net user  
- **Lessons:** Learned user privilege basics and common mistakes  
![Screenshot](images/windowsfund.png)

---

---

### 💻 HTB - DNS in Details

-**Problem: **Understand and analyze DNS record types, domain hierarchy, and DNS request behaviors
**Approach:** Studied DNS structure (TLDs, subdomains), queried DNS records (A, AAAA, CNAME, MX, TXT) using practical tools in the TryHackMe lab environment
-**Tools:** DNS lookup interface, TryHackMe DNS simulator
-**Lessons:** Learned how to retrieve IP addresses, email server info, CNAME chains, and domain verification data using DNS queries
![Screenshot](assets/images/dns-in-details.jpg)

---

## 📬 Contact

- 📧 **Email:** [daina.muiruri@gmail.com](mailto:daina.muiruri@gmail.com)  
- 📞 **Phone:** +254 795 551 432  
- 💼 **LinkedIn:** [linkedin.com/in/daina-muiruri-0154b81a3](https://www.linkedin.com/in/daina-muiruri-0154b81a3/)  
- 💻 **GitHub:** [github.com/DAINAWAMBUI](https://github.com/DAINAWAMBUI)

---

© 2025 Daina Muiruri. All Rights Reserved.
