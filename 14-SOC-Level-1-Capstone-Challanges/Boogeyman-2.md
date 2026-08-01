# 👻 Boogeyman 2 — TryHackMe Room
---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → SOC Level 1 Capstone Challenges  
**Difficulty:** Medium  
**Room Link:** https://tryhackme.com/room/boogeyman2  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Boogeyman 2** continues the Boogeyman incident series, placing you in the role of a SOC Analyst investigating a sophisticated **spear phishing attack targeting the Human Resources department**. Unlike generic phishing campaigns, the attacker carefully crafts emails specifically for HR personnel to gain initial access to the organization's network.

The room focuses on identifying targeted phishing techniques, analyzing malicious emails, investigating endpoint activity, and correlating evidence to understand the attacker’s objectives.

---

# 🎯 Learning Objectives

- Investigate spear phishing campaigns
- Analyze targeted phishing emails
- Inspect malicious attachments
- Detect endpoint compromise
- Identify attacker techniques
- Correlate investigation artifacts
- Build an attack timeline
- Identify Indicators of Compromise (IOCs)
- Perform threat hunting
- Conduct a complete SOC investigation

---

# 📌 Task 1 — Introduction

Introduced the attack scenario and investigation objectives.

Topics covered:

- Incident overview
- Targeted attack scenario
- Investigation workflow
- Available evidence
- SOC analyst responsibilities

---

# 📌 Task 2 — Spear Phishing Human Resources

Investigated a highly targeted phishing email sent to Human Resources staff.

Analysis included:

- Email Header Analysis
- Sender Verification
- Targeted Social Engineering
- Attachment Inspection
- Message Authenticity
- Phishing Indicators
- Email Routing
- Suspicious Domains
- Delivery Techniques
- Initial Access Vector

---

# 🛡️ Skills Practiced

- Spear Phishing Investigation
- Email Forensics
- Header Analysis
- Threat Hunting
- IOC Identification
- Endpoint Investigation
- Incident Response
- Threat Correlation
- SOC Investigation
- Attack Timeline Reconstruction

---

# 🔑 Key Concepts

- Spear Phishing
- Social Engineering
- Email Headers
- Initial Access
- Targeted Attacks
- Indicators of Compromise (IOCs)
- Endpoint Detection
- Threat Intelligence
- Incident Analysis
- Attack Attribution

---

# ⚔️ Attack Chain Investigated

1. Reconnaissance of target organization
2. Targeted spear phishing email crafted
3. Delivery to Human Resources
4. Malicious attachment distributed
5. User interaction
6. Initial system compromise
7. Investigation of attacker activity
8. Identification of attack indicators

---

# 📊 Evidence Sources

### Email Evidence

- Email Headers
- Sender Information
- Routing Information
- Authentication Results
- Attachments
- Embedded URLs

### Endpoint Evidence

- Process Creation Logs
- File Artifacts
- Windows Event Logs
- Execution History
- User Activity

### Threat Intelligence

- Malicious Domains
- IP Addresses
- File Hashes
- IOC Databases
- Reputation Sources

---

# 🚨 Indicators Investigated

- Suspicious Sender Address
- Spoofed Domains
- Malicious Attachments
- Embedded URLs
- Phishing Indicators
- File Hashes
- Suspicious Processes
- External Connections
- Known Malicious Infrastructure
- IOC Correlation

---

# 🔄 Investigation Workflow

1. Review phishing report
2. Analyze email headers
3. Verify sender authenticity
4. Inspect attachment
5. Examine embedded links
6. Investigate endpoint activity
7. Correlate logs
8. Identify attacker infrastructure
9. Build attack timeline
10. Document findings

---

# 💡 SOC Investigation Tips

- Spear phishing attacks are highly personalized—always examine the context of the message.
- Verify sender domains rather than relying on display names.
- Investigate every attachment before execution.
- Correlate email evidence with endpoint telemetry to confirm compromise.
- Use threat intelligence to validate suspicious domains, IP addresses, and file hashes.

---

# 💬 Key Takeaway

> "Boogeyman 2 highlights how targeted spear phishing campaigns can bypass traditional defenses by exploiting trust and human behavior. Successful SOC investigations require combining email forensics, endpoint analysis, and threat intelligence to uncover the complete attack."

---

# 🚀 Skills Gained

- Spear Phishing Analysis
- Email Header Investigation
- Threat Intelligence Correlation
- IOC Identification
- Endpoint Investigation
- Incident Response
- Threat Hunting
- Attack Timeline Reconstruction
- Social Engineering Detection
- SOC Level 1 Investigation Workflow
