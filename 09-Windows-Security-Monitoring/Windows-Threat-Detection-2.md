# 🪟 Windows Threat Detection 2 — TryHackMe Room
---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Windows Security Monitoring  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/windowsthreatdetection2  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Windows Threat Detection 2** focuses on detecting attacker activity after gaining initial access to a Windows system. The room explores the **Discovery** and **Collection** phases of the MITRE ATT&CK framework, teaching SOC analysts how to identify reconnaissance behavior and suspicious data collection through Windows logs, Sysmon events, and endpoint monitoring.

---

# 🎯 Learning Objectives

- Understand the Discovery phase
- Detect system reconnaissance activities
- Identify Collection techniques
- Analyze Windows security logs
- Detect attacker enumeration
- Improve endpoint monitoring skills

---

# 📌 Task 1 — Introduction

Introduced the objectives of detecting attacker activity after initial compromise and explained the importance of monitoring post-exploitation behavior.

---

# 📌 Task 2 — Discovery Overview

Learned how attackers gather information about compromised systems before moving laterally or escalating privileges.

Covered:

- System discovery
- Network discovery
- User enumeration
- Process discovery
- Environment reconnaissance

---

# 📌 Task 3 — Detecting Discovery

Explored methods for identifying reconnaissance activity using Windows Event Logs and Sysmon telemetry.

Focused on:

- Suspicious command execution
- Process creation events
- PowerShell activity
- Command-line auditing
- Enumeration detection

---

# 📌 Task 4 — Collection Overview

Introduced techniques attackers use to gather valuable information before exfiltration.

Studied:

- Sensitive file collection
- Credential collection
- Screenshot capture
- Clipboard access
- Local data gathering

---

# 📌 Task 5 — Detecting Collection

Learned how SOC analysts detect suspicious data collection behavior.

Covered:

- File access monitoring
- Unusual process activity
- Archive creation
- Credential dumping indicators
- Data staging detection

---

# 🛡️ Skills Practiced

- Windows Threat Detection
- Discovery Detection
- Collection Detection
- Windows Event Log Analysis
- Sysmon Monitoring
- Process Analysis
- Command-Line Investigation
- Endpoint Monitoring

---

# 🔑 Key Concepts

- MITRE ATT&CK Discovery
- MITRE ATT&CK Collection
- System Enumeration
- Process Creation
- PowerShell Logging
- Sysmon Events
- Data Collection
- Credential Access
- Endpoint Telemetry
- Threat Hunting

---

# 💬 Key Takeaway

> "After compromising a system, attackers typically perform discovery and collection activities before achieving their objectives. Detecting these behaviors through Windows logs, Sysmon, and endpoint telemetry enables SOC analysts to identify threats before data theft or lateral movement occurs."

---

# 🚀 Next Steps

- Windows Threat Detection 3
- Lateral Movement Detection
- Privilege Escalation Detection
- Sysmon Advanced Hunting
- Microsoft Defender
- Threat Hunting
- Incident Response
- Endpoint Detection and Response (EDR)
