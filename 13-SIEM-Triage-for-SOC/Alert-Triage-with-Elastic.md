# 🔎 Alert Triage with Elastic — TryHackMe Room
---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → SIEM Triage for SOC  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/alerttriagewithelastic  
**Status:** ✔ Completed

---

# 🧠 Room Overview

This room introduces the **Elastic Security (ELK Stack)** platform and demonstrates how SOC analysts investigate security alerts using Elastic. Through realistic attack scenarios, analysts correlate logs, examine endpoint activity, analyze web attacks, trace user behavior, and detect malicious command execution.

The room focuses on using Elastic to identify attacker techniques and validate security alerts during incident investigations.

---

# 🎯 Learning Objectives

- Understand Elastic Security fundamentals
- Investigate alerts using Elastic
- Analyze web attack indicators
- Track suspicious user activity
- Detect malicious command execution
- Correlate multiple log sources
- Improve SOC alert triage skills

---

# 📌 Task 1 — Introduction

Introduced the Elastic Security platform and its role in modern SOC environments.

Topics covered:

- Elastic Security
- SIEM functionality
- Alert investigation
- Threat detection workflow

---

# 📌 Task 2 — Scenario Briefing

Reviewed the investigation scenario before beginning analysis.

Analysts learned to:

- Understand the alert context
- Identify affected assets
- Determine investigation scope
- Gather initial evidence

---

# 📌 Task 3 — Investigating Web Attacks

Analyzed suspicious web activity to identify possible attacks.

Evidence reviewed:

- HTTP requests
- URL paths
- Request methods
- Response codes
- Source IP addresses
- User-Agent strings
- Web server logs

Common attack indicators:

- Directory traversal
- SQL Injection
- XSS attempts
- Web shell uploads
- Suspicious POST requests
- Enumeration activity

---

# 📌 Task 4 — Uncovering Account Activity

Investigated user account behavior after suspicious activity was detected.

Reviewed:

- Login events
- Authentication attempts
- User sessions
- Account usage
- Privilege changes
- Failed logins
- Successful authentications

Objective:

Determine whether an attacker successfully authenticated or abused user credentials.

---

# 📌 Task 5 — Exposing Command Execution

Investigated suspicious process execution on compromised systems.

Evidence analyzed:

- Process creation events
- Parent-child process relationships
- Command-line arguments
- Script execution
- PowerShell activity
- Shell commands
- Endpoint telemetry

Indicators of compromise:

- Encoded PowerShell
- cmd.exe abuse
- Bash execution
- LOLBins
- Reverse shell activity
- Suspicious child processes

---

# 🛡️ Skills Practiced

- Elastic Security
- SIEM Investigation
- Alert Triage
- Log Correlation
- Endpoint Analysis
- Web Attack Investigation
- Account Activity Analysis
- Process Investigation
- Threat Hunting
- Incident Response

---

# 🔑 Key Concepts

- Elastic SIEM
- Endpoint Telemetry
- Alert Investigation
- Event Correlation
- Web Logs
- Authentication Logs
- Process Monitoring
- Command Execution
- IOC Validation
- Threat Detection

---

# 🔍 Investigation Workflow

1. Receive security alert
2. Review alert metadata
3. Identify affected endpoint
4. Investigate web activity
5. Analyze user authentication
6. Examine endpoint processes
7. Correlate related events
8. Build attack timeline
9. Validate malicious activity
10. Document findings

---

# 📊 Evidence Sources

### Endpoint

- Process Creation
- Parent Processes
- Command Lines
- PowerShell Logs
- File Activity

### Authentication

- Login Events
- Failed Logins
- User Sessions
- Privilege Changes

### Web

- Access Logs
- Error Logs
- URLs
- HTTP Methods
- User-Agent
- Source IP

### Network

- Connections
- Destination Hosts
- IP Addresses
- Ports

---

# 💡 SOC Investigation Tips

- Always investigate alerts in context.
- Correlate endpoint, authentication, and web logs.
- Build an attack timeline before making conclusions.
- Look for attacker behavior rather than isolated events.
- Validate every alert before escalating.

---

# 💬 Key Takeaway

> "Elastic Security enables SOC analysts to rapidly investigate alerts by correlating endpoint, authentication, web, and network telemetry. Effective alert triage depends on understanding attacker behavior, validating evidence, and distinguishing true threats from normal activity."

---

# 🚀 Next Steps

- Elastic Query Language (EQL)
- Kibana Dashboards
- Detection Rules
- Threat Hunting
- MITRE ATT&CK Mapping
- Sigma Rules
- Endpoint Detection & Response (EDR)
- Incident Response
- Detection Engineering
- Advanced Elastic Security
