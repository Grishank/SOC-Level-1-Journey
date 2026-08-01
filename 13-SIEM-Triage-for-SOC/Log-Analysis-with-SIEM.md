# 📊 Log Analysis with SIEM — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Log-Analysis-with-SIEM-banner.png?raw=true" alt="Log Analysis with SIEM Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → SIEM Triage for SOC  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/loganalysiswithsiem  
**Status:** ✔ Completed

---

# 🧠 Room Overview

This room introduces how **Security Information and Event Management (SIEM)** platforms help SOC analysts collect, normalize, correlate, and analyze logs from multiple systems. It explains the importance of centralized logging, common log sources, and how analysts investigate suspicious activities using SIEM solutions.

---

# 🎯 Learning Objectives

- Understand the purpose of SIEM platforms
- Learn why centralized logging is important
- Identify common log sources
- Understand Windows, Linux, and Web logs
- Learn how analysts investigate security events
- Build foundational log analysis skills

---

# 📌 Task 1 — Introduction

Learned the role of SIEM in modern Security Operations Centers (SOC).

Topics covered:

- What SIEM is
- Why organizations use SIEM
- Centralized monitoring
- Security visibility

---

# 📌 Task 2 — Benefits of SIEM for Analysts

Explored how SIEM platforms improve SOC operations.

Key benefits include:

- Centralized log collection
- Faster investigations
- Correlation of events
- Automated alerting
- Threat detection
- Incident response support
- Long-term log retention

---

# 📌 Task 3 — Log Sources Overview

Studied the different types of logs ingested into SIEM solutions.

Common log sources:

- Windows Event Logs
- Linux System Logs
- Web Server Logs
- Firewall Logs
- IDS/IPS Logs
- Authentication Logs
- VPN Logs
- DNS Logs
- Proxy Logs
- Endpoint Security Logs

---

# 📌 Task 4 — Windows Logs

Learned about Windows Event Logs used during investigations.

Common log categories:

- Security Logs
- System Logs
- Application Logs
- PowerShell Logs
- Sysmon Logs

Typical events monitored:

- User logins
- Failed authentication
- Account creation
- Privilege escalation
- Service creation
- Process execution

---

# 📌 Task 5 — Linux Logs

Explored common Linux log files.

Important logs:

- Authentication logs
- Syslog
- Kernel logs
- Audit logs
- SSH logs
- Service logs

Used for detecting:

- SSH brute force
- Privilege escalation
- Service abuse
- Unauthorized access
- System modifications

---

# 📌 Task 6 — Web Application Logs

Studied web server logs used during investigations.

Common information includes:

- Client IP
- Request method
- URL requested
- Response code
- User-Agent
- Timestamp
- Referrer

Useful for detecting:

- Web attacks
- Directory traversal
- SQL Injection
- XSS attempts
- Brute-force attacks
- Reconnaissance

---

# 🛡️ Skills Practiced

- SIEM Fundamentals
- Log Analysis
- Security Monitoring
- Event Correlation
- Windows Event Logs
- Linux Log Analysis
- Web Log Analysis
- SOC Investigation
- Threat Detection
- Security Visibility

---

# 🔑 Key Concepts

- Security Information and Event Management (SIEM)
- Centralized Logging
- Log Correlation
- Security Events
- Alert Generation
- Event Investigation
- Threat Detection
- Incident Response
- Log Sources
- Security Monitoring

---

# 🧰 Log Sources Covered

### Windows

- Security Event Logs
- System Logs
- Application Logs
- PowerShell Logs
- Sysmon Logs

### Linux

- Syslog
- Auth Logs
- Audit Logs
- Kernel Logs
- SSH Logs

### Web

- Apache Logs
- Nginx Logs
- Access Logs
- Error Logs

---

# 💡 SIEM Investigation Workflow

1. Collect logs from endpoints and servers
2. Normalize log formats
3. Correlate related events
4. Generate alerts
5. Investigate suspicious activity
6. Validate findings
7. Escalate incidents if required
8. Document the investigation

---

# 💬 Key Takeaway

> "A SIEM transforms massive volumes of security logs into actionable intelligence by centralizing data, correlating events, and helping SOC analysts quickly detect, investigate, and respond to threats across Windows, Linux, web applications, and network infrastructure."

---

# 🚀 Next Steps

- Splunk
- Microsoft Sentinel
- Elastic SIEM
- QRadar
- Advanced Log Correlation
- Detection Engineering
- Sigma Rules
- Threat Hunting
- Incident Response
- SOC Case Management
