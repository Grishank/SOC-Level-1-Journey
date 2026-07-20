# 🔺 Pyramid of Pain — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Pyramid-Of-Pain-banner.png?raw=true" alt="Pyramid of Pain Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1  
**Module:** Cyber Defence Frameworks  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/pyramidofpainax  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

This room introduces the **Pyramid of Pain**, a cybersecurity model that ranks Indicators of Compromise (IOCs) based on how difficult they are for attackers to change after being detected.

The room focuses on:
- Indicators of Compromise (IOCs)
- Pyramid of Pain model
- Threat hunting
- Detection strategies
- Adversary behavior

---

# 🎯 Learning Objectives

- Understand the Pyramid of Pain
- Learn different types of IOCs
- Understand attacker adaptation
- Learn why behavioral detection is important
- Improve threat hunting knowledge

---

# 📌 Task 1 — Introduction

Learned how the Pyramid of Pain helps defenders prioritize detections that have the greatest impact on attackers.

---

# 🔑 Task 2 — Hash Values (Trivial)

- File hashes (MD5, SHA1, SHA256)
- Easy for attackers to change
- Useful for malware identification

---

# 🌐 Task 3 — IP Address (Easy)

Attackers can change IP addresses using:
- VPS providers
- VPNs
- Proxies
- Botnets

IP-based detections provide only temporary protection.

---

# 🌍 Task 4 — Domain Names (Simple)

Malicious domains can be blocked, but attackers can quickly register new ones.

Examples:
- Command & Control (C2) domains
- Phishing domains

---

# 💻 Task 5 — Host Artifacts (Annoying)

Host artifacts include traces left on compromised systems, such as:

- Registry changes
- Files
- Services
- Scheduled tasks
- Process execution

Changing these artifacts requires more effort from attackers.

---

# 🌐 Task 6 — Network Artifacts (Annoying)

Network artifacts include:

- HTTP headers
- DNS requests
- User-Agent strings
- Network traffic patterns

These are harder for attackers to modify consistently.

---

# 🛠️ Task 7 — Tools (Challenging)

Security teams can detect attacker tools such as:

- Mimikatz
- PsExec
- Metasploit
- Cobalt Strike

Changing tools forces attackers to modify their workflows.

---

# 🎯 Task 8 — TTPs (Tough)

TTPs (**Tactics, Techniques, and Procedures**) represent attacker behavior.

Examples:
- Lateral movement
- Privilege escalation
- Persistence
- Credential dumping

Behavioral detections based on TTPs are the most difficult for attackers to evade.

---

# 🧪 Task 9 — Practical: The Pyramid of Pain

Applied Pyramid of Pain concepts by identifying different IOC types and understanding which detections create the greatest operational cost for attackers.

---

# 🔍 Key Concepts Learned

- Pyramid of Pain
- Indicators of Compromise (IOCs)
- Threat Hunting
- TTPs
- Behavioral Detection
- Adversary Detection Strategy

---

# 💬 Key Takeaway

> “The higher you detect in the Pyramid of Pain, the harder it becomes for attackers to adapt and continue their operations.”

---

# 🚀 Next Steps

- Learn the MITRE ATT&CK Framework
- Practice threat hunting
- Study behavioral analytics
- Explore IOC enrichment techniques
- Build detection rules using TTPs
