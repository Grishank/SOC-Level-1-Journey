# 🐚 Detecting Web Shells — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Detecting-Web-Shells-banner.png?raw=true" alt="Detecting Web Shells Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Web Security Monitoring  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/detectingwebshells  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Detecting Web Shells** focuses on identifying malicious web shells by analyzing web server logs, file systems, and network traffic. The room teaches how attackers deploy web shells after compromising a web application and how SOC analysts can detect their presence through forensic artifacts and behavioral indicators.

---

# 🎯 Learning Objectives

- Understand what web shells are
- Learn how web shells operate
- Analyze web shell structures
- Detect web shells using logs
- Investigate beyond traditional logging
- Perform web shell incident investigations

---

# 📌 Task 1 — Introduction

Introduced the objectives of web shell detection and explained why web shells are commonly used to maintain persistence after compromising a web server.

---

# 📌 Task 2 — Web Shell Overview

Learned what web shells are and how attackers use them to execute commands remotely.

Covered:

- Remote command execution
- Persistence
- Backdoors
- Post-exploitation
- Common web shell types

---

# 📌 Task 3 — Anatomy of a Web Shell

Explored the internal structure and behavior of web shells.

Studied:

- PHP web shells
- Command execution functions
- Obfuscation techniques
- File upload abuse
- Malicious scripts

---

# 📌 Task 4 — Log-Based Detection

Learned how server logs help identify web shell activity.

Analyzed:

- Suspicious HTTP requests
- POST requests
- Unusual URL patterns
- Error logs
- Access logs

---

# 📌 Task 5 — Beyond Logs

Explored additional methods for detecting web shells outside traditional logging.

Focused on:

- File integrity monitoring
- File system analysis
- Network traffic analysis
- Persistence detection
- Behavioral indicators

---

# 📌 Task 6 — Investigation

Applied investigation techniques to identify a compromised web server and uncover web shell activity.

Practiced:

- Evidence collection
- IOC identification
- Timeline analysis
- Attack reconstruction
- Incident response

---

# 🛡️ Skills Practiced

- Web Shell Detection
- Log Analysis
- File System Investigation
- Network Traffic Analysis
- Incident Investigation
- Threat Hunting
- IOC Identification
- Digital Forensics

---

# 🔑 Key Concepts

- Web Shells
- Backdoors
- Persistence
- Remote Command Execution
- File Integrity Monitoring
- Access Logs
- HTTP POST Requests
- Indicators of Compromise (IOCs)
- Threat Hunting
- Incident Response

---

# 💬 Key Takeaway

> "Detecting web shells requires combining log analysis, file system monitoring, and network traffic investigation to uncover persistent backdoors that attackers leave behind after exploiting web applications."

---

# 🚀 Next Steps

- Web Log Analysis
- Incident Response
- Digital Forensics
- Malware Analysis
- Threat Hunting
- SIEM Investigations
- File Integrity Monitoring
- Advanced Web Security Monitoring
