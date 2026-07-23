# 🛡️ The Greenholt Phish — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/The-Greenholt-Phish-banner.png?raw=true" alt="The Greenholt Phish Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Phishing Analysis  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/phishingemails5fgjlzxc  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**The Greenholt Phish** is a practical SOC investigation challenge where a suspicious email is analyzed from start to finish. The room combines everything learned throughout the Phishing Analysis module, requiring investigation of email headers, sender information, SPF/DMARC records, attachments, hashes, VirusTotal intelligence, and Indicators of Compromise (IOCs).

This simulates the workflow of a SOC analyst handling a real phishing incident.

---

# 🎯 Learning Objectives

- Analyze a suspicious phishing email
- Investigate email headers
- Verify sender authenticity
- Trace email origin
- Examine SPF and DMARC records
- Analyze malicious attachments
- Calculate file hashes
- Investigate files using VirusTotal
- Identify Indicators of Compromise (IOCs)

---

# 📌 Scenario

A sales executive at **Greenholt PLC** reports a suspicious email from what appears to be a known customer. The email contains several red flags:

- Generic greeting
- Unexpected money transfer request
- Suspicious attachment
- Unusual communication style

The Security Operations Center (SOC) is tasked with determining whether the email is legitimate or a phishing attempt.

---

# 🔍 Investigation Steps

## 1. Email Metadata Analysis

Extracted important information including:

- Transfer Reference Number
- Sender display name
- Sender email address
- Reply-To address
- Subject line

This helps identify impersonation attempts and suspicious sender behavior.

---

## 2. Email Header Analysis

Analyzed email headers to determine:

- Originating IP address
- Sending mail server
- Return-Path
- Reply-To mismatch
- Authentication results

Header analysis is one of the most valuable techniques for phishing investigations.

---

## 3. Source Verification

Investigated the originating IP address and infrastructure.

Verified:

- IP ownership
- Hosting provider
- Geographic information
- Reputation

This helps determine whether the sender originated from legitimate infrastructure.

---

## 4. Email Authentication Checks

Performed authentication verification using DNS records.

### SPF

Verified Sender Policy Framework (SPF) configuration to determine whether the sending server was authorized.

### DMARC

Reviewed DMARC policy to understand how the domain protects against spoofing attacks.

---

## 5. Attachment Analysis

Investigated the suspicious attachment by identifying:

- Filename
- File hash (SHA-256)
- Actual file type
- File size

Calculated the SHA-256 hash for further threat intelligence lookups.

---

## 6. VirusTotal Investigation

Used VirusTotal to gather threat intelligence about the attachment.

Collected information including:

- Detection ratio
- File reputation
- Malware classification
- Community analysis
- Behavioral indicators

VirusTotal provides valuable context for determining whether a file is malicious.

---

## 7. Indicators of Compromise (IOCs)

Identified multiple IOCs from the investigation, including:

- Suspicious sender email
- Reply-To mismatch
- Originating IP
- Attachment filename
- SHA-256 hash
- Malicious infrastructure
- Email authentication anomalies

These artifacts can be added to detection rules or blocklists.

---
<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Phish-Hunter-badge.png?raw=true" alt="The Greenholt Phish Banner" width="900"/>
</p>
---

# 🛡️ Tools Used

- Email Header Analyzer
- SPF Lookup
- DMARC Lookup
- SHA-256 Hashing
- VirusTotal
- DNS Investigation

---

# 🔑 Skills Practiced

- Email Forensics
- Header Analysis
- DNS Investigation
- Threat Intelligence
- IOC Collection
- Malware Triage
- File Hash Analysis
- Attachment Investigation

---

# 📚 Key Concepts Learned

- Email spoofing detection
- Header verification
- Reply-To abuse
- SPF validation
- DMARC policies
- Threat intelligence enrichment
- Malware attachment investigation
- IOC extraction

---

# 💬 Key Takeaway

> "A successful phishing investigation combines email header analysis, authentication checks, threat intelligence, and attachment analysis to determine whether an email is malicious. Even a convincing phishing email leaves artifacts that a SOC analyst can use to uncover the attack."

---

# 🚀 Next Steps

- Malware Analysis
- Threat Intelligence
- Digital Forensics
- SOC Alert Investigation
- Incident Response
- Advanced Email Forensics
- Detection Engineering
