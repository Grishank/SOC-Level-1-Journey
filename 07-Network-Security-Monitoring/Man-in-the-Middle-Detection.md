# 🕵️ Man-in-the-Middle Detection — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Man-in-the-Middle-Detection-banner.png?raw=true" alt="Man-in-the-Middle Detection Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Network Security Monitoring  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/mitmdetection  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Man-in-the-Middle Detection** introduces one of the most common network attacks where an adversary secretly intercepts communication between two systems. The room explains how MITM attacks work, the techniques attackers use, and how defenders can identify their presence through network traffic analysis.

It provides practical experience detecting ARP spoofing, DNS spoofing, and SSL stripping using network monitoring techniques commonly employed by SOC analysts.

---

# 🎯 Learning Objectives

- Understand Man-in-the-Middle (MITM) attacks
- Learn common MITM techniques
- Detect ARP spoofing attacks
- Identify DNS spoofing activity
- Recognize SSL stripping attacks
- Analyze network traffic for MITM indicators
- Improve network defense capabilities

---

# 📌 Task 1 — Introduction

Introduced the fundamentals of Man-in-the-Middle attacks and their impact on network security.

---

# 📌 Task 2 — Lab Connection

Connected to the virtual lab environment for investigating various MITM attack scenarios.

---

# 📌 Task 3 — MITM Attacks: An Overview

Learned how attackers position themselves between victims and legitimate systems.

Covered:

- MITM attack lifecycle
- Traffic interception
- Credential theft
- Session hijacking
- Traffic manipulation

---

# 📌 Task 4 — Detecting ARP Spoofing

Explored how attackers manipulate ARP communications to redirect network traffic.

Focused on:

- ARP poisoning
- Duplicate MAC addresses
- ARP cache manipulation
- Suspicious ARP replies
- Network anomalies

---

# 📌 Task 5 — Unmasking DNS Spoofing

Investigated how attackers forge DNS responses to redirect victims to malicious websites.

Covered:

- DNS cache poisoning
- Fake DNS responses
- Malicious redirection
- Domain impersonation
- DNS traffic analysis

---

# 📌 Task 6 — Spotting SSL Stripping in Action

Learned how attackers downgrade encrypted HTTPS connections to insecure HTTP.

Examined:

- HTTPS downgrade attacks
- SSL stripping
- Missing TLS encryption
- Insecure redirects
- Certificate anomalies

---

# 🛡️ Skills Practiced

- MITM Detection
- ARP Analysis
- DNS Traffic Analysis
- HTTPS Inspection
- Network Monitoring
- Packet Analysis
- Threat Hunting
- Security Investigation

---

# 🔑 Key Concepts

- Man-in-the-Middle (MITM)
- ARP Spoofing
- ARP Poisoning
- DNS Spoofing
- DNS Cache Poisoning
- SSL Stripping
- HTTPS Downgrade
- Session Hijacking
- Network Traffic Analysis
- Indicators of Compromise (IOCs)

---

# 💬 Key Takeaway

> "Man-in-the-Middle attacks rely on silently intercepting network communications. Monitoring ARP, DNS, and HTTPS traffic enables defenders to detect manipulation attempts before attackers can steal credentials or sensitive information."

---

# 🚀 Next Steps

- Wireshark Traffic Analysis
- NetworkMiner
- Zeek Network Monitoring
- Suricata IDS
- Network Threat Hunting
- Packet Analysis
- Incident Response
- Network Forensics
