# 🕷️ ItsyBitsy — TryHackMe Room
---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → SIEM Triage for SOC  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/itsybitsy  
**Status:** ✔ Completed

---

# 🧠 Room Overview

ItsyBitsy is a practical SOC investigation challenge where you act as a Security Analyst investigating a **Command-and-Control (C2) communication alert**. Using Splunk and multiple log sources, you analyze network traffic, endpoint telemetry, DNS requests, and process activity to determine whether the alert represents malicious activity.

The room emphasizes building an investigation timeline, validating Indicators of Compromise (IOCs), and identifying attacker behavior rather than relying on a single alert.

---

# 🎯 Learning Objectives

- Investigate a Command-and-Control (C2) alert
- Analyze logs using Splunk
- Correlate multiple security events
- Identify attacker communication
- Build an attack timeline
- Validate Indicators of Compromise (IOCs)
- Improve SOC investigation methodology

---

# 📌 Task 1 — Introduction

Introduced the investigation scenario and objectives.

Topics covered:

- SOC investigation workflow
- Splunk environment
- Alert context
- Incident analysis methodology

---

# 📌 Task 2 — Scenario: Investigate a Potential C2 Communication Alert

Investigated a suspected Command-and-Control communication between an endpoint and an external server.

During the investigation, analyzed:

- DNS queries
- Network connections
- HTTP requests
- Process execution
- Endpoint logs
- User activity
- Security alerts

Objective:

Determine whether the endpoint is communicating with an attacker-controlled infrastructure.

---

# 🛡️ Skills Practiced

- Splunk Investigation
- SIEM Alert Triage
- Command & Control Detection
- IOC Validation
- Network Traffic Analysis
- DNS Investigation
- Endpoint Analysis
- Process Investigation
- Threat Hunting
- Incident Response

---

# 🔑 Key Concepts

- Command & Control (C2)
- Indicators of Compromise (IOC)
- DNS Analysis
- Network Telemetry
- Endpoint Telemetry
- Event Correlation
- Timeline Analysis
- Threat Intelligence
- Alert Validation
- Security Investigation

---

# 🔍 Investigation Workflow

1. Review the security alert
2. Identify the affected endpoint
3. Examine DNS queries
4. Analyze outbound network traffic
5. Investigate suspicious processes
6. Correlate endpoint and network logs
7. Validate attacker infrastructure
8. Build an attack timeline
9. Confirm or dismiss the alert
10. Document investigation findings

---

# 📊 Evidence Sources

### Network Logs

- DNS Queries
- HTTP Requests
- HTTPS Connections
- Source IP
- Destination IP
- Ports
- External Domains

### Endpoint Logs

- Process Creation
- Parent Processes
- Command Line
- User Activity
- File Execution

### Authentication Logs

- User Logins
- Account Activity
- Session Information

### Threat Intelligence

- Known Malicious Domains
- Suspicious IP Addresses
- IOC Reputation
- External Intelligence Sources

---

# 🚨 Indicators Investigated

- Unknown external domains
- Repeated outbound connections
- Suspicious DNS lookups
- Encoded PowerShell commands
- Unusual process execution
- Unexpected network traffic
- Malware communication patterns

---

# 💡 SOC Investigation Tips

- Investigate the entire attack chain, not just the alert.
- Correlate DNS, endpoint, and network logs together.
- Validate suspicious domains using threat intelligence.
- Build a timeline to understand attacker behavior.
- Confirm malicious communication before escalating the incident.

---

# 💬 Key Takeaway

> "Command-and-Control detection relies on correlating endpoint activity with network communications. A SOC analyst must validate suspicious outbound connections, investigate related processes, and use threat intelligence to distinguish legitimate traffic from attacker-controlled infrastructure."

---

# 🚀 Next Steps

- Advanced Splunk Searches (SPL)
- Network Threat Hunting
- DNS Threat Hunting
- Malware Traffic Analysis
- Sigma Detection Rules
- MITRE ATT&CK Mapping
- Threat Intelligence Integration
- Detection Engineering
- Incident Response
- Advanced SOC Investigations
