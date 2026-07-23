# 🎣 Snapped Phish-ing Line — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Snapped-Phish-ing-Line-banner.png?raw=true" alt="Snapped Phish-ing Line Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Phishing Analysis  
**Difficulty:** Medium  
**Room Link:** https://tryhackme.com/room/snappedphishingline  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Snapped Phish-ing Line** is an end-to-end phishing investigation challenge where multiple phishing emails are analyzed to uncover an entire phishing campaign. Rather than examining a single malicious email, this room focuses on identifying phishing infrastructure, tracing redirection URLs, analyzing phishing kits, collecting threat intelligence, and extracting attacker Indicators of Compromise (IOCs).

This room closely mirrors a real-world SOC investigation involving credential harvesting and phishing infrastructure analysis.

---

# 🎯 Learning Objectives

- Analyze multiple phishing email samples
- Investigate phishing URLs and redirections
- Identify attacker infrastructure
- Retrieve and inspect phishing kits
- Perform threat intelligence lookups
- Analyze phishing kit contents
- Investigate credential harvesting
- Extract Indicators of Compromise (IOCs)

---

# 📌 Scenario

Several employees at **SwiftSpend Financial** report suspicious emails requesting account verification. Unfortunately, some employees have already entered their credentials into a fake login page and can no longer access their accounts.

As a SOC analyst, the objective is to investigate the phishing campaign, determine how the attack was conducted, identify compromised infrastructure, and collect evidence for incident response.

---

# 🔍 Investigation Steps

## 1. Email Analysis

Reviewed multiple phishing emails to identify:

- Targeted recipients
- Sender addresses
- Subject lines
- Malicious attachments
- Embedded phishing URLs

Comparing multiple emails helped identify patterns used throughout the phishing campaign.

---

## 2. URL Investigation

Analyzed phishing URLs to determine:

- Redirect chains
- Root domains
- Hosted phishing pages
- Impersonated services

URL analysis revealed the infrastructure supporting the credential harvesting attack.

---

## 3. Fake Login Page Analysis

Opened the phishing page inside the isolated lab environment and verified:

- Brand impersonation
- Login form behavior
- Credential collection methods
- Phishing page structure

Understanding impersonated services helps SOC analysts quickly classify phishing campaigns.

---

## 4. Phishing Kit Discovery

Located exposed directories on the attacker-controlled server and downloaded the phishing kit archive for further analysis.

Collected information including:

- Archive filename
- SHA-256 hash
- File size
- Archive contents

This demonstrated how attacker operational mistakes can expose their own tooling.

---

## 5. Threat Intelligence

Investigated the phishing kit using VirusTotal to gather intelligence about:

- Detection results
- Malware categorization
- Community analysis
- File metadata
- Archive contents

Threat intelligence enriches investigations with additional context about attacker activity.

---

## 6. Credential Harvesting Investigation

Examined captured credential logs within the phishing kit to identify:

- Victim email addresses
- Multiple login attempts
- Credential collection workflow

This phase illustrates how compromised credentials are typically stored by phishing operators.

---

## 7. Phishing Kit Analysis

Inspected the phishing kit source code to locate:

- Credential collection scripts
- Destination email addresses
- Configuration files
- Embedded attacker artifacts

Reviewing the kit exposed additional attacker infrastructure and operational details.

---

## 8. Indicator of Compromise (IOC) Collection

Collected numerous IOCs throughout the investigation, including:

- Malicious sender email addresses
- Phishing domains
- Redirect URLs
- Credential collection email
- SHA-256 hashes
- Archive filenames
- Victim email addresses
- Exposed infrastructure

These indicators can be added to SIEM detection rules, threat intelligence platforms, and blocklists.

---

# 🛠️ Tools Used

- VirusTotal
- CyberChef
- SHA-256 Hashing
- URL Analysis
- DNS Investigation
- Web Browser (Lab Environment)
- Threat Intelligence Resources

---

# 🔑 Skills Practiced

- Email Forensics
- URL Analysis
- Threat Intelligence
- IOC Collection
- Phishing Kit Analysis
- Credential Harvesting Investigation
- Malware Triage
- Web Investigation

---

# 📚 Key Concepts Learned

- Multi-email phishing investigations
- URL redirection analysis
- Credential harvesting techniques
- Phishing infrastructure discovery
- Threat intelligence enrichment
- Phishing kit analysis
- IOC extraction
- Campaign correlation

---

# 💬 Key Takeaway

> "Modern phishing investigations extend beyond email analysis. By tracing phishing URLs, analyzing attacker infrastructure, inspecting phishing kits, and collecting Indicators of Compromise, SOC analysts can uncover the full scope of an attack and better protect their organization from future campaigns."

---

# 🚀 Next Steps

- Advanced Threat Intelligence
- Malware Analysis
- Digital Forensics
- Incident Response
- Threat Hunting
- Detection Engineering
- Web Application Security
- SOC Investigations
