# 🪟 Windows Threat Detection 3 — TryHackMe Room

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Windows Security Monitoring  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/windowsthreatdetection3  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Windows Threat Detection 3** focuses on how attackers maintain long-term access to compromised Windows systems through **Command and Control (C2)** and **Persistence** techniques. The room teaches SOC analysts how to detect malicious persistence mechanisms such as scheduled tasks, services, Run Keys, and startup folders using Windows logs, Sysmon, and endpoint monitoring.

---

# 🎯 Learning Objectives

- Understand Command and Control (C2)
- Detect persistence techniques
- Monitor scheduled tasks and services
- Identify malicious Run Keys
- Detect startup folder persistence
- Improve Windows threat hunting skills

---

# 📌 Task 1 — Introduction

Introduced the objectives of detecting post-compromise persistence mechanisms used by attackers to maintain access.

---

# 📌 Task 2 — Command and Control

Learned how compromised hosts communicate with attacker-controlled infrastructure.

Covered:

- C2 communication
- Beaconing
- Remote commands
- Malware communication
- Network monitoring

---

# 📌 Task 3 — Persistence Overview

Introduced common persistence techniques used after initial compromise.

Studied:

- Windows persistence
- Registry abuse
- Startup programs
- Scheduled execution
- Service abuse

---

# 📌 Task 4 — Persistence: Tasks and Services

Explored how attackers create scheduled tasks and malicious Windows services.

Focused on:

- Scheduled Tasks
- Windows Services
- Service creation
- Persistence detection
- Event monitoring

---

# 📌 Task 5 — Persistence: Run Keys and Startup

Learned how registry Run Keys and Startup folders are abused to launch malware automatically.

Covered:

- Registry Run Keys
- Startup Folder
- Autorun entries
- Registry monitoring
- Startup persistence

---

# 📌 Task 6 — Impact and Threat Detection Recap

Reviewed the complete attack lifecycle and discussed effective detection strategies for persistent threats.

Summarized:

- C2 detection
- Persistence monitoring
- Windows logging
- Threat hunting
- Incident response

---

# 🛡️ Skills Practiced

- Windows Threat Detection
- Command and Control Detection
- Persistence Detection
- Registry Monitoring
- Scheduled Task Analysis
- Windows Service Analysis
- Startup Monitoring
- Threat Hunting

---

# 🔑 Key Concepts

- Command and Control (C2)
- Persistence
- Scheduled Tasks
- Windows Services
- Registry Run Keys
- Startup Folder
- Autoruns
- Windows Event Logs
- Sysmon
- Endpoint Detection

---

# 💬 Key Takeaway

> "Attackers often rely on persistence mechanisms such as scheduled tasks, Windows services, Run Keys, and startup folders to survive system reboots. Detecting these techniques early through Windows logs, Sysmon, and endpoint monitoring is essential for preventing long-term compromise."

---

# 🚀 Next Steps

- Windows Threat Detection 4
- Privilege Escalation Detection
- Lateral Movement Detection
- Advanced Sysmon Hunting
- Microsoft Defender
- Threat Hunting
- Incident Response
- Endpoint Detection and Response (EDR)
