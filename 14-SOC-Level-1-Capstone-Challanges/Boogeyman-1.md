# 👻 Boogeyman 1 — TryHackMe Room
---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → SOC Level 1 Capstone Challenges  
**Difficulty:** Medium  
**Room Link:** https://tryhackme.com/room/boogeyman1  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Boogeyman 1** simulates a real-world phishing attack against an organization where a malicious email leads to malware execution and suspicious financial activity. As a SOC Analyst, you investigate the attack by analyzing email headers, endpoint evidence, and network traffic to reconstruct the attack timeline and identify the threat.

The room provides hands-on experience with email forensics, endpoint investigation, and network traffic analysis during a phishing incident.

---

# 🎯 Learning Objectives

- Analyze phishing emails
- Examine email headers
- Identify malicious attachments
- Investigate endpoint artifacts
- Analyze malware execution
- Inspect network communications
- Correlate evidence across multiple data sources
- Build an attack timeline
- Identify Indicators of Compromise (IOCs)
- Perform an end-to-end phishing investigation

---

# 📌 Task 1 — Introduction: New Threat in Town

Introduced the phishing incident and investigation scenario.

Topics covered:

- Incident overview
- Investigation objectives
- Available evidence
- Attack scenario
- SOC workflow

---

# 📌 Task 2 — Email Analysis: Look at that Headers!

Investigated the phishing email to determine its legitimacy and identify attacker infrastructure.

Covered:

- Email Header Analysis
- Sender Verification
- Return-Path Analysis
- SPF/DKIM/DMARC Checks
- Message Routing
- Suspicious Domains
- Malicious Attachments
- Social Engineering Indicators

---

# 📌 Task 3 — Endpoint Security: Are You Sure That's an Invoice?

Investigated the compromised endpoint after the malicious attachment was opened.

Analysis included:

- Process Creation
- Parent-Child Process Relationships
- PowerShell Activity
- Suspicious Executables
- File System Changes
- Malware Execution
- Persistence Indicators
- Windows Event Logs

---

# 📌 Task 4 — Network Traffic Analysis: They Got Us. Call the Bank Immediately!

Analyzed network communications generated after malware execution.

Observed:

- DNS Requests
- HTTP/HTTPS Traffic
- External Connections
- Command and Control (C2)
- File Downloads
- Suspicious IP Addresses
- Malicious Domains
- Data Exfiltration Indicators

---

# 🛡️ Skills Practiced

- Email Forensics
- Header Analysis
- Phishing Investigation
- Endpoint Investigation
- Malware Analysis
- Network Traffic Analysis
- IOC Identification
- Threat Hunting
- Attack Timeline Reconstruction
- Incident Response

---

# 🔑 Key Concepts

- Phishing
- Email Headers
- Social Engineering
- Malware Delivery
- Endpoint Detection
- PowerShell Abuse
- Network Indicators
- Command and Control (C2)
- Indicators of Compromise (IOCs)
- Threat Correlation

---

# ⚔️ Attack Chain Investigated

1. Phishing email delivered
2. Malicious attachment opened
3. Malware executed
4. Suspicious processes spawned
5. External network communication established
6. Command-and-Control traffic observed
7. Potential financial fraud activity detected
8. Incident investigated and contained

---

# 📊 Evidence Sources

### Email Evidence

- Email Headers
- Sender Information
- Message Metadata
- Attachment Details
- Authentication Results

### Endpoint Evidence

- Windows Event Logs
- Process Tree
- Executables
- File Artifacts
- Registry Changes

### Network Evidence

- DNS Queries
- HTTP Requests
- External IP Connections
- Domain Lookups
- Network Sessions

---

# 🚨 Indicators Investigated

- Suspicious Email Headers
- Spoofed Sender Address
- Malicious Attachment
- Suspicious PowerShell Commands
- Unknown Executables
- External C2 IP Addresses
- Malicious Domains
- Unusual Network Activity
- File Hashes
- IOC Correlation

---

# 🔄 Investigation Workflow

1. Review phishing email
2. Analyze email headers
3. Validate sender authenticity
4. Examine attachment
5. Investigate endpoint activity
6. Trace malware execution
7. Analyze network traffic
8. Identify attacker infrastructure
9. Correlate evidence
10. Build incident timeline
11. Document findings

---

# 💡 SOC Investigation Tips

- Never trust the visible sender name—always inspect the full email headers.
- Correlate email artifacts with endpoint and network telemetry.
- Parent-child process relationships often reveal malicious execution chains.
- Verify suspicious domains and IP addresses using threat intelligence.
- Build a complete timeline before determining the attack's impact.

---

# 💬 Key Takeaway

> "Boogeyman 1 demonstrates how a single phishing email can lead to a full security incident. Effective SOC investigations require correlating email, endpoint, and network evidence to uncover the complete attack chain and respond quickly."

---

# 🚀 Skills Gained

- Phishing Email Analysis
- Email Header Investigation
- Endpoint Forensics
- Malware Investigation
- Network Traffic Analysis
- IOC Identification
- Threat Intelligence Correlation
- Incident Response
- Attack Timeline Reconstruction
- SOC Level 1 Investigation Workflow
