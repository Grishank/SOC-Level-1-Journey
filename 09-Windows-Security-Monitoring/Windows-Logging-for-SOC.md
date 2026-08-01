# 🪟 Windows Logging for SOC — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Windows-Logging-for-SOC-banner.png?raw=true" alt="Windows Logging for SOC Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Windows Security Monitoring  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/windowsloggingforsoc  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Windows Logging for SOC** introduces the Windows logging ecosystem and teaches SOC analysts how to use Windows Event Logs, Sysmon, and PowerShell logging to detect malicious activity. The room focuses on understanding key security events related to authentication, user management, process creation, network connections, and command execution.

---

# 🎯 Learning Objectives

- Understand Windows Event Logging
- Learn what Windows records in its logs
- Analyze authentication events
- Monitor user account activity
- Detect suspicious processes with Sysmon
- Investigate file, network, and PowerShell activity

---

# 📌 Task 1 — Introduction

Introduced Windows logging and explained its importance in threat detection and incident investigations.

---

# 📌 Task 2 — What Is Logged

Explored the different types of events recorded by Windows.

Covered:

- Security logs
- System logs
- Application logs
- Event IDs
- Windows Event Viewer

---

# 📌 Task 3 — Security Log: Authentication

Learned how Windows records authentication events for user logins.

Focused on:

- Successful logons
- Failed logons
- Logon types
- Authentication events
- Security Event IDs

---

# 📌 Task 4 — Security Log: User Management

Explored events related to account administration.

Studied:

- User creation
- Account deletion
- Group membership changes
- Privilege assignments
- Account modifications

---

# 📌 Task 5 — Sysmon: Process Monitoring

Learned how Sysmon provides detailed visibility into process activity.

Covered:

- Process creation
- Parent-child processes
- Command-line logging
- Process identifiers
- Suspicious execution chains

---

# 📌 Task 6 — Sysmon: Files and Network

Explored Sysmon events related to file operations and network communications.

Focused on:

- File creation
- File modifications
- Network connections
- DNS queries
- Indicators of malicious behavior

---

# 📌 Task 7 — PowerShell: Logging Commands

Learned how PowerShell logging helps detect malicious scripting activity.

Analyzed:

- Script Block Logging
- Module Logging
- PowerShell transcripts
- Encoded commands
- Command execution history

---

# 🛡️ Skills Practiced

- Windows Event Log Analysis
- Authentication Monitoring
- User Activity Monitoring
- Sysmon Analysis
- Process Investigation
- Network Connection Monitoring
- PowerShell Investigation
- Threat Detection

---

# 🔑 Key Concepts

- Windows Event Logs
- Event Viewer
- Security Logs
- Authentication Events
- User Management
- Sysmon
- Process Creation
- Network Connections
- File Monitoring
- PowerShell Logging

---

# 💬 Key Takeaway

> "Windows Event Logs, Sysmon, and PowerShell logging provide comprehensive visibility into system activity, enabling SOC analysts to detect suspicious behavior, investigate incidents, and identify attacker techniques."

---

# 🚀 Next Steps

- Sysmon Deep Dive
- Windows Event IDs
- Splunk Log Analysis
- Microsoft Defender
- Sigma Rules
- Threat Hunting
- Incident Response
- Windows Forensics
