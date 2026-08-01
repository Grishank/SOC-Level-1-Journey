# 👻 Boogeyman 3 — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Boogeyman-Slayer.png?raw=true" alt="Boogeyman badge" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → SOC Level 1 Capstone Challenges  
**Difficulty:** Hard  
**Room Link:** https://tryhackme.com/room/boogeyman3  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Boogeyman 3** is the final chapter of the Boogeyman investigation series. You step into the role of a SOC Analyst responding to an active security incident after the Boogeyman threat actor has successfully infiltrated an organization's environment.

Unlike the previous rooms that focused primarily on phishing, this challenge requires correlating multiple forensic artifacts, endpoint evidence, and attacker activity to understand how the compromise unfolded and determine the full scope of the intrusion.

---

# 🎯 Learning Objectives

- Investigate an advanced security incident
- Analyze endpoint artifacts
- Correlate attack evidence
- Identify attacker behavior
- Detect persistence mechanisms
- Investigate malicious processes
- Build a complete attack timeline
- Identify Indicators of Compromise (IOCs)
- Perform threat hunting
- Conduct an end-to-end SOC investigation

---

# 📌 Task 1 — Introduction

Introduced the incident scenario and investigation objectives.

Topics covered:

- Incident overview
- Attack background
- Available evidence
- Investigation workflow
- SOC analyst responsibilities

---

# 📌 Task 2 — The Chaos Inside

Investigated the compromised environment to identify attacker activity and reconstruct the intrusion.

Analysis included:

- Endpoint Investigation
- Process Analysis
- Event Log Review
- Suspicious Process Creation
- Persistence Mechanisms
- PowerShell Activity
- File System Changes
- User Activity
- Timeline Correlation
- IOC Identification

---

# 🛡️ Skills Practiced

- Incident Response
- Threat Hunting
- Endpoint Investigation
- Windows Forensics
- Malware Investigation
- IOC Identification
- Log Analysis
- Attack Timeline Reconstruction
- Threat Intelligence Correlation
- SOC Investigation

---

# 🔑 Key Concepts

- Initial Access
- Persistence
- Endpoint Detection
- Windows Event Logs
- Process Analysis
- PowerShell Abuse
- Threat Hunting
- Indicators of Compromise (IOCs)
- Incident Response
- Attack Timeline

---

# ⚔️ Attack Chain Investigated

1. Initial compromise
2. Malicious process execution
3. Endpoint compromise
4. Persistence establishment
5. Attacker activity
6. Evidence collection
7. IOC identification
8. Timeline reconstruction
9. Incident containment

---

# 📊 Evidence Sources

### Endpoint Evidence

- Windows Event Logs
- Security Logs
- Process Creation Logs
- File System Artifacts
- Registry Entries
- Scheduled Tasks

### Host Artifacts

- Running Processes
- Executables
- Parent-Child Process Relationships
- User Activity
- PowerShell History

### Threat Intelligence

- File Hashes
- Domains
- IP Addresses
- IOC Databases
- Malware Indicators

---

# 🚨 Indicators Investigated

- Suspicious Processes
- Malicious PowerShell Commands
- Persistence Mechanisms
- Unknown Executables
- File Hashes
- Registry Changes
- Scheduled Tasks
- External Connections
- IOC Correlation
- Attacker Artifacts

---

# 🔄 Investigation Workflow

1. Review the incident
2. Collect forensic evidence
3. Analyze endpoint activity
4. Investigate process execution
5. Identify persistence
6. Correlate Windows logs
7. Validate IOCs
8. Build the attack timeline
9. Assess attacker objectives
10. Document findings

---

# 💡 SOC Investigation Tips

- Always investigate parent-child process relationships to uncover hidden execution chains.
- Correlate endpoint evidence with Windows event logs for accurate timeline reconstruction.
- Persistence mechanisms often reveal how attackers intend to maintain long-term access.
- Validate suspicious artifacts using threat intelligence before drawing conclusions.
- Focus on understanding the attacker's objectives, not just the malware.

---

# 💬 Key Takeaway

> "Boogeyman 3 demonstrates that effective incident response requires piecing together evidence from multiple sources to reconstruct the attack. Successful SOC analysts combine endpoint forensics, log analysis, and threat intelligence to understand the full scope of an intrusion."

---

# 🚀 Skills Gained

- Advanced Incident Investigation
- Endpoint Forensics
- Windows Threat Hunting
- IOC Identification
- Log Correlation
- Persistence Analysis
- Threat Intelligence Correlation
- Attack Timeline Reconstruction
- Incident Response
- SOC Level 1 Investigation Workflow
