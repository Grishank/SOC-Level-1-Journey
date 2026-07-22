# 🛡️ Phishing Analysis Tools — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Phishing-Analysis-Tools-banner.png?raw=true" alt="Phishing Analysis Tools Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Phishing Analysis  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/phishingemails3tryoe  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

**Phishing Analysis Tools** introduces the tools and techniques SOC analysts use to investigate phishing emails. The room focuses on analyzing email artifacts, inspecting email headers and bodies, identifying Indicators of Compromise (IOCs), using malware sandbox services, and leveraging dedicated phishing analysis platforms.

Instead of manually inspecting every email component, analysts learn how specialized tools accelerate phishing investigations.

---

# 🎯 Learning Objectives

- Identify phishing artifacts
- Analyze email headers
- Inspect email bodies
- Investigate Indicators of Compromise (IOCs)
- Analyze suspicious attachments safely
- Use malware sandbox platforms
- Investigate phishing campaigns with PhishTool

---

# 📌 Task 1 — Introduction

Learned the workflow SOC analysts follow when investigating phishing emails and the importance of collecting evidence before making a verdict.

---

# 📌 Task 2 — Identifying Artifacts

Studied common phishing artifacts, including:

- Sender email addresses
- Domains
- IP addresses
- URLs
- File hashes
- Attachments
- Indicators of Compromise (IOCs)

---

# 📌 Task 3 — Email Header Analysis

Analyzed email headers to verify authenticity.

Examined:

- From
- Reply-To
- Return-Path
- Received headers
- SPF results
- DKIM validation
- DMARC authentication
- Message-ID

Learned how headers expose spoofed or malicious emails.

---

# 📌 Task 4 — Email Body Analysis

Inspected phishing email content for:

- Social engineering tactics
- Suspicious hyperlinks
- Fake login portals
- Credential harvesting attempts
- Urgent language
- Grammar inconsistencies
- Brand impersonation

---

# 📌 Task 5 — Malware Sandboxes

Learned how malware sandbox platforms safely execute suspicious files without risking production systems.

Covered concepts such as:

- Behavioral analysis
- Network activity
- Process creation
- Registry modifications
- File system changes

---

# 📌 Task 6 — Using PhishTool

Explored **PhishTool**, a phishing investigation platform that helps analysts:

- Parse phishing emails
- Extract IOCs
- Review email headers
- Analyze attachments
- Investigate URLs
- Generate investigation reports

---

# 📌 Task 7 — Your Account Is on Hold

Performed a practical investigation of a phishing email impersonating an account notification.

Focused on:

- Sender verification
- Link analysis
- Header inspection
- Authentication checks
- IOC identification

---

# 📌 Task 8 — Update Payment Details

Investigated a payment-themed phishing campaign designed to steal financial information.

Analyzed:

- Fake payment requests
- Credential theft pages
- Domain reputation
- Embedded phishing URLs

---

# 📌 Task 9 — Excel Executable

Examined a malicious Microsoft Excel attachment.

Learned to identify:

- Macro-enabled documents
- Embedded malware
- Suspicious file behavior
- Safe attachment analysis using sandbox environments

---

# 🛡️ Tools Covered

- PhishTool
- Malware Sandboxes
- Email Header Analysis
- IOC Investigation
- URL Analysis
- Hash Analysis

---

# 🔑 Key Concepts

- Indicators of Compromise (IOCs)
- Email Header Analysis
- Malware Sandbox
- PhishTool
- URL Investigation
- File Hashes
- Attachment Analysis
- SPF
- DKIM
- DMARC

---

# 💬 Key Takeaway

> "Effective phishing investigations combine manual analysis with specialized tools to validate email authenticity, identify malicious artifacts, and safely analyze suspicious attachments before determining the overall threat."

---

# 🚀 Next Steps

- Phishing Incident Response
- Threat Intelligence Integration
- Malware Analysis
- Digital Forensics
- SOC Alert Investigation
- Email Security Operations
