# 🔍 File and Hash Threat Intel — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/File-and-Hash-Threat-Intel-banner.png?raw=true" alt="File and Hash Threat Intel Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Threat Analysis Tools  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/fileandhashthreatintel  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**File and Hash Threat Intel** focuses on enriching suspicious files and file hashes using cyber threat intelligence. It demonstrates how SOC analysts investigate malware by analyzing filenames, file paths, cryptographic hashes, sandbox reports, and external threat intelligence platforms to determine whether a file is malicious.

---

# 🎯 Learning Objectives

- Understand file-based threat intelligence
- Learn how file hashes identify malware
- Investigate suspicious filenames and file paths
- Perform hash lookups using threat intelligence services
- Analyze malware inside sandbox environments
- Practice real-world threat intelligence investigations

---

# 📌 Task 1 — Introduction

Introduced the importance of enriching suspicious files using external intelligence.

Covered:

- Why file artifacts matter
- Malware identification
- Threat intelligence enrichment

---

# 📌 Task 2 — Filenames and Paths

Learned how attackers often disguise malicious files.

Covered:

- Suspicious filenames
- Common malware locations
- Windows system directories
- User profile locations
- Temporary folders
- Startup folders

Identified indicators such as:

- Random filenames
- Double extensions
- Executables in unusual directories
- Masquerading techniques

---

# 📌 Task 3 — File Hash Lookup

Learned how cryptographic hashes uniquely identify files.

Covered:

- MD5
- SHA1
- SHA256

Performed threat intelligence lookups using online databases to determine whether a file had previously been identified as malicious.

Learned how hash reputation assists SOC investigations.

---

# 📌 Task 4 — Sandbox Analysis

Explored automated malware analysis environments.

Learned to review:

- File behavior
- Process creation
- Registry changes
- Network connections
- File system activity
- Indicators of Compromise (IOCs)

Understood how sandbox reports help analysts safely observe malware execution.

---

# 📌 Task 5 — Threat Intelligence Challenge

Applied all previously learned concepts in a practical investigation.

Performed:

- File enrichment
- Hash reputation checks
- Sandbox report analysis
- IOC identification
- Threat assessment

Used gathered intelligence to determine whether suspicious files were malicious.

---

# 🛡️ Skills Practiced

- File Investigation
- Malware Identification
- Hash Analysis
- Threat Intelligence
- IOC Analysis
- Sandbox Analysis
- Malware Triage
- Threat Enrichment

---

# 🔑 Key Concepts

- File Hashes
- MD5
- SHA1
- SHA256
- File Reputation
- Indicators of Compromise (IOCs)
- Sandbox Analysis
- Malware Behavior
- File Paths
- Malware Triage
- Threat Intelligence Enrichment

---

# 🧰 Tools & Platforms Introduced

- VirusTotal
- Hybrid Analysis
- Any.Run
- Joe Sandbox
- Threat Intelligence Platforms
- Hash Lookup Services

---

# 💬 Key Takeaway

> "A file's hash acts as its digital fingerprint. By combining file metadata, hash reputation, sandbox behavior, and threat intelligence, SOC analysts can rapidly determine whether a suspicious file poses a threat and prioritize incident response effectively."

---

# 🚀 Next Steps

- Malware Analysis
- YARA Rules
- IOC Hunting
- Threat Hunting
- Digital Forensics
- Memory Analysis
- SIEM Investigation
- Windows Event Logs
- Malware Reverse Engineering
- Incident Response
