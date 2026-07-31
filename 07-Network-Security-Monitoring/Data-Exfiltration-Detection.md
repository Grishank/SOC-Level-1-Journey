# 📤 Data Exfiltration Detection — TryHackMe Room

---

**Platform:** TryHackMe  
**Path:** SOC Level 1 → Network Security Monitoring  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/dataexfildetection  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Data Exfiltration Detection** teaches how attackers steal sensitive data from compromised environments and how defenders can identify these activities through network monitoring. The room explores common exfiltration techniques, indicators of compromise, and detection methods across multiple network protocols including DNS, FTP, HTTP, and ICMP.

It provides practical knowledge that helps SOC analysts recognize suspicious outbound traffic before confidential data leaves the organization.

---

# 🎯 Learning Objectives

- Understand data exfiltration techniques
- Identify indicators of data theft
- Detect DNS tunneling
- Analyze FTP-based exfiltration
- Monitor HTTP data transfers
- Detect ICMP tunneling
- Improve network monitoring skills

---

# 📌 Task 1 — Introduction

Introduced the concept of data exfiltration and explained why detecting outbound data transfers is a critical responsibility for SOC analysts.

---

# 📌 Task 2 — Lab Connection

Connected to the virtual lab environment used throughout the room for investigating different exfiltration scenarios.

---

# 📌 Task 3 — Data Exfiltration Overview

Learned how attackers move stolen information outside an organization's network.

Covered:

- Data exfiltration lifecycle
- Common attacker techniques
- Indicators of compromise
- Suspicious outbound traffic
- Data theft scenarios

---

# 📌 Task 4 — Detection: Data Exfiltration through DNS Tunneling

Explored how attackers abuse DNS queries to secretly transmit sensitive information.

Focused on:

- DNS tunneling
- Encoded DNS requests
- Abnormal query patterns
- Long domain names
- High DNS request volume

---

# 📌 Task 5 — Detection: Data Exfiltration through FTP

Analyzed how FTP can be abused for unauthorized file transfers.

Examined:

- FTP uploads
- File transfer monitoring
- Authentication events
- Large outbound transfers
- FTP traffic analysis

---

# 📌 Task 6 — Detection: Data Exfiltration via HTTP

Learned how attackers disguise stolen data inside normal web traffic.

Covered:

- HTTP POST requests
- Web uploads
- Suspicious destinations
- Large HTTP payloads
- Web traffic monitoring

---

# 📌 Task 7 — Detection: Data Exfiltration via ICMP

Investigated how attackers use ICMP packets as covert communication channels.

Focused on:

- ICMP tunneling
- Ping abuse
- Covert channels
- Packet size anomalies
- Unusual ICMP traffic

---

# 🛡️ Skills Practiced

- Data Exfiltration Detection
- DNS Traffic Analysis
- HTTP Traffic Analysis
- FTP Monitoring
- ICMP Analysis
- Network Monitoring
- Threat Hunting
- Security Log Analysis

---

# 🔑 Key Concepts

- Data Exfiltration
- DNS Tunneling
- FTP Abuse
- HTTP POST Exfiltration
- ICMP Tunneling
- Outbound Traffic
- Indicators of Compromise (IOCs)
- Covert Channels
- Network Monitoring
- Threat Detection

---

# 💬 Key Takeaway

> "Successful attackers eventually need to move stolen data outside the network. Monitoring outbound traffic across protocols such as DNS, HTTP, FTP, and ICMP enables defenders to detect and stop data exfiltration before sensitive information is lost."

---

# 🚀 Next Steps

- Zeek Network Monitoring
- Suricata IDS
- Wireshark Traffic Analysis
- Threat Hunting
- Network Forensics
- SIEM Detection Rules
- Incident Response
- Malware Traffic Analysis
