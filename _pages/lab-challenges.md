---
permalink: /lab-challenges/
title: "Lab Challenges"

---

# 🧪 Lab Challenges

This section showcases hands-on lab-based challenges I've completed as part of my training in cybersecurity. Each challenge strengthened my skills in system enumeration, vulnerability exploitation, and technical analysis.

---

## 🔐 **1. HTB Academy - ACADEMY-GETSTART-SKILLS**

**Platform:** Hack The Box (HTB)  
**Category:** Beginner / Skill Development

### 🧩 Problem Statement
Gain access to a virtual machine using enumeration and weak credentials.

### 🛠️ Approach & Tools Used
- Ran **Nmap** to identify open ports and services.
- Discovered an HTTP login panel on port 80.
- Used **Hydra** to perform brute-force attack against the login page.
- Identified weak credentials and logged in successfully.

### 📸 Screenshot
![HTB Screenshot](images/getstart.png)  *(replace with actual screenshot filename)*

### 🎯 Lessons Learned
- The importance of service and port enumeration.
- How default or weak credentials can be exploited.
- Basic web login brute-force methodology using Hydra.

---

## 💻 **2. HTB Academy - Windows Fundamentals**

**Platform:** Hack The Box Academy  
**Category:** Windows Enumeration

### 🧩 Problem Statement
Explore and understand the Windows file system, user management, and access rights.

### 🛠️ Approach & Tools Used
- Accessed the VM via RDP and used **Command Prompt** and **PowerShell**.
- Explored user groups using `net user` and `whoami`.
- Checked running processes, startup services, and firewall rules.
- Navigated and audited Windows folders and registry keys.

### 📸 Screenshot
![Windows Fundamentals Screenshot](images/windowsfund.png)

### 🎯 Lessons Learned
- Gained practical skills in using native Windows tools for security auditing.
- Understood file permission structures and how misconfigurations create vulnerabilities.
- Learned how to assess the system baseline in a Windows environment.

---

## 🏁 **More Labs Coming Soon**

I am actively working through more labs, including:
- Linux privilege escalation walkthroughs
- Web application security challenges
- Network scanning and exploitation using tools like Burp Suite, Nikto, and Wireshark

Stay tuned for updates on this section!

---
