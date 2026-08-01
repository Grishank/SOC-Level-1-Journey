# 🛡️ Benign — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Benign-banner.png?raw=true" alt="Benign Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → SIEM Triage for SOC  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/benign  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Benign** is a hands-on SOC investigation challenge where you analyze security logs to determine whether an endpoint has been compromised. Acting as a SOC Analyst, you investigate suspicious alerts, examine endpoint and authentication logs, correlate evidence, and identify the infected host while distinguishing malicious activity from normal system behavior.

The room reinforces the importance of evidence-based investigations and avoiding false positives during incident response.

---

# 🎯 Learning Objectives

- Investigate a potentially infected host
- Correlate multiple log sources
- Identify malicious activity
- Differentiate benign from malicious events
- Build an attack timeline
- Validate Indicators of Compromise (IOCs)
- Practice real SOC investigation methodology

---

# 📌 Task 1 — Introduction

Introduced the investigation scenario and objectives.

Topics covered:

- SOC investigation workflow
- Incident analysis methodology
- Log correlation
- Threat validation

---

# 📌 Task 2 — Scenario: Identify and Investigate an Infected Host

Performed a complete investigation to determine whether a host had been compromised.

Investigation included:

- Reviewing security alerts
- Examining authentication events
- Investigating process creation logs
- Analyzing network activity
- Reviewing endpoint telemetry
- Correlating suspicious events
- Identifying Indicators of Compromise (IOCs)
- Confirming the infected system

Objective:

Determine whether the activity represents a real compromise or legitimate system behavior.

---

# 🛡️ Skills Practiced

- SIEM Investigation
- Alert Triage
- Endpoint Analysis
- IOC Validation
- Event Correlation
- Threat Hunting
- Timeline Analysis
- Incident Investigation
- Security Monitoring
- SOC Workflow

---

# 🔑 Key Concepts

- Infected Host Identification
- Alert Validation
- False Positive Analysis
- Event Correlation
- Endpoint Telemetry
- Authentication Analysis
- Indicators of Compromise (IOC)
- Security Investigation
- Incident Response
- Threat Detection

---

# 🔍 Investigation Workflow

1. Review the security alert
2. Identify the affected host
3. Examine authentication logs
4. Investigate process execution
5. Analyze network connections
6. Correlate endpoint events
7. Validate IOCs
8. Build an attack timeline
9. Confirm or dismiss the compromise
10. Document investigation findings

---

# 📊 Evidence Sources

### Endpoint Logs

- Process Creation
- Parent Processes
- Command Line Arguments
- File Activity
- Service Activity

### Authentication Logs

- Successful Logins
- Failed Logins
- User Sessions
- Account Activity

### Network Logs

- Source IP
- Destination IP
- Outbound Connections
- DNS Queries

### Security Logs

- Alert Details
- Detection Rules
- Endpoint Telemetry
- Investigation Timeline

---

# 🚨 Indicators Investigated

- Suspicious process execution
- Unexpected network connections
- Unusual authentication activity
- Malicious parent-child processes
- Persistence indicators
- Command execution
- Suspicious file activity
- Known Indicators of Compromise (IOCs)

---

# 💡 SOC Investigation Tips

- Never assume an alert is malicious without evidence.
- Correlate multiple log sources before reaching conclusions.
- Build a timeline to understand attacker behavior.
- Separate legitimate administrative activity from malicious actions.
- Validate all indicators before escalating an incident.

---

# 💬 Key Takeaway

> "Effective SOC investigations rely on evidence, not assumptions. By correlating authentication, endpoint, and network telemetry, analysts can accurately identify compromised systems while minimizing false positives and ensuring only genuine threats are escalated."

---

# 🚀 Next Steps

- Advanced Threat Hunting
- Splunk SPL Queries
- Elastic Security
- Sigma Detection Rules
- MITRE ATT&CK Mapping
- Detection Engineering
- Malware Analysis
- Digital Forensics
- Incident Response
- Advanced SOC Investigations
