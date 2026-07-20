# 🚪 Eviction — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Eviction-banner.png?raw=true" alt="Eviction Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1  
**Module:** Cyber Defence Frameworks  
**Difficulty:** Medium  
**Room Link:** https://tryhackme.com/room/eviction  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

**Eviction** is a practical threat hunting challenge that uses the **MITRE ATT&CK Framework** to investigate an APT intrusion. As a SOC analyst, the objective is to identify the attacker's Tactics, Techniques, and Procedures (TTPs) and determine how to detect and stop them throughout the attack lifecycle.

The room focuses on:
- MITRE ATT&CK practical usage
- Threat hunting
- APT investigation
- ATT&CK Navigator
- Detection engineering

---

# 🎯 Learning Objectives

- Analyze an APT campaign using MITRE ATT&CK
- Identify attacker TTPs
- Map adversary behavior to ATT&CK techniques
- Understand attacker progression through the kill chain
- Improve detection and hunting capabilities

---

# 📌 Task 1 — Understand the Adversary

Investigated a simulated APT28 campaign against an organization and used the MITRE ATT&CK Navigator to answer practical investigation questions.

Identified attacker behavior across multiple ATT&CK tactics including:

- Reconnaissance
- Resource Development
- Initial Access
- Execution
- Persistence
- Defense Evasion
- Discovery
- Lateral Movement
- Collection
- Exfiltration
- Command and Control

---

# 🔍 Threat Hunting Activities

Throughout the investigation, identified techniques such as:

- Spearphishing Links
- Email Account Compromise
- Malicious Files & Links
- PowerShell & Windows Command Shell
- Registry Run Keys
- Rundll32 Proxy Execution
- Network Sniffing
- SMB / Windows Admin Shares
- SharePoint Data Collection
- Proxy-based Command & Control

Each activity was mapped to the appropriate ATT&CK technique to understand the attacker's objectives and possible detections.

---

# 🛡️ Defensive Focus

The investigation emphasized how defenders can:

- Hunt for attacker artifacts
- Detect persistence mechanisms
- Monitor lateral movement
- Identify credential abuse
- Detect command execution
- Monitor data collection and exfiltration
- Strengthen MITRE ATT&CK-based detections

---

# 🔍 Key Concepts Learned

- MITRE ATT&CK Navigator
- Threat Hunting
- APT Investigation
- ATT&CK Technique Mapping
- Detection Engineering
- Adversary Emulation
- Defensive Monitoring

---

# 💬 Key Takeaway

> “Understanding an attacker's TTPs through MITRE ATT&CK enables defenders to detect, investigate, and evict adversaries before they achieve their objectives.”

---
<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Skilled-Navigator-badge.png?raw=true" alt="Eviction Banner" width="900"/>
</p>

---

# 🚀 Next Steps

- Practice advanced threat hunting labs
- Learn Sigma rule creation
- Build ATT&CK detection mappings
- Explore Purple Team exercises
- Study real-world APT campaigns
