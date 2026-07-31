# 🦈 Wireshark: Traffic Analysis — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Wireshark-badge.png?raw=true" alt="Wireshark Traffic Analysis Banner" width="900"/>
</p>

---

**Platform:** TryHackMe                                                                                                                           
**Path:** SOC Level 1 → Network Traffic Analysis                                                                                                                     
**Difficulty:** Medium                                                                                                          
**Room Link:** https://tryhackme.com/room/wiresharktrafficanalysis  
**Status:** ✔ Completed

---

# 🧠 Room Overview

**Wireshark: Traffic Analysis** builds on the fundamentals of packet operations by teaching how to detect anomalies and malicious activity within captured network traffic. The room walks through analyzing scans, ARP poisoning, host identification, tunneling, cleartext protocols, and encrypted traffic — reinforcing how attackers' actions appear at the packet level.

These skills are critical for SOC analysts and incident responders tasked with identifying reconnaissance, credential theft, and malicious traffic during live investigations.

---

# 🎯 Learning Objectives

- Detect and analyze Nmap scan traffic
- Identify ARP poisoning and Man-in-the-Middle attacks
- Identify hosts using DHCP, NetBIOS, and Kerberos traffic
- Recognize tunneling activity through DNS and ICMP
- Analyze cleartext protocols (FTP, HTTP) for exposed data
- Decrypt and inspect HTTPS traffic
- Hunt for cleartext credentials in captures
- Translate findings into actionable investigation results

---

# 📌 Task 1 — Introduction

Introduced the goal of the room: using Wireshark to move beyond the basics and actively hunt for anomalies, suspicious behavior, and attacker activity within network captures.

---

# 📌 Task 2 — Nmap Scans

Analyzed packet captures containing Nmap scan traffic to identify reconnaissance activity.

Covered:
- Identifying scan patterns in Wireshark
- Differentiating scan types (SYN, Connect, etc.)
- Recognizing signs of network reconnaissance

---

# 📌 Task 3 — ARP Poisoning & Man In The Middle!

Investigated ARP poisoning attacks and how they enable Man-in-the-Middle (MITM) positioning on a network.

Covered:
- ARP protocol behavior
- Signs of ARP spoofing/poisoning in captures
- Identifying MITM attack indicators

---

# 📌 Task 4 — Identifying Hosts: DHCP, NetBIOS and Kerberos

Learned how to fingerprint and identify hosts on a network using protocol traffic.

Covered:
- DHCP lease requests and host discovery
- NetBIOS name resolution traffic
- Kerberos authentication traffic
- Mapping hosts to usernames and hostnames

---

# 📌 Task 5 — Tunneling Traffic: DNS and ICMP

Explored how attackers abuse DNS and ICMP protocols to tunnel data and evade detection.

Covered:
- DNS tunneling indicators
- ICMP tunneling indicators
- Identifying abnormal packet sizes and frequency
- Detecting covert channels in traffic

---

# 📌 Task 6 — Cleartext Protocol Analysis: FTP

Analyzed FTP traffic captures to identify exposed data transmitted in cleartext.

Covered:
- FTP protocol structure in Wireshark
- Extracting credentials from FTP sessions
- Identifying file transfer activity

---

# 📌 Task 7 — Cleartext Protocol Analysis: HTTP

Analyzed HTTP traffic to identify sensitive information sent without encryption.

Covered:
- Following HTTP streams
- Extracting credentials and form data
- Identifying suspicious HTTP requests

---

# 📌 Task 8 — Encrypted Protocol Analysis: Decrypting HTTPS

Learned how to decrypt HTTPS traffic in Wireshark using session keys for deeper inspection.

Covered:
- TLS/SSL handshake basics
- Using key logs to decrypt HTTPS
- Inspecting decrypted application data

---

# 📌 Task 9 — Bonus: Hunt Cleartext Credentials!

Applied filtering and analysis techniques to hunt for cleartext credentials across mixed protocol traffic.

Covered:
- Combining filters across protocols
- Credential-hunting workflow
- Practical detection of exposed authentication data

---

# 📌 Task 10 — Bonus: Actionable Results!

Focused on translating packet-level findings into actionable security outcomes for reporting and response.

Covered:
- Summarizing investigation findings
- Prioritizing actionable indicators
- Communicating results effectively

---

# 📌 Task 11 — Conclusion

Reviewed the complete traffic analysis workflow, reinforcing how combining protocol knowledge, filtering, and decryption techniques enables analysts to detect and investigate malicious activity in real captures.

---

# 🛡️ Skills Practiced

- Network Traffic Analysis
- Reconnaissance Detection
- ARP Poisoning Detection
- Host Identification
- Tunneling Detection
- Cleartext Protocol Analysis
- HTTPS Decryption
- Credential Hunting
- Incident Response Reporting

---

# 🔑 Key Concepts

- Nmap Scan Detection
- ARP Spoofing / MITM
- DHCP, NetBIOS, Kerberos
- DNS & ICMP Tunneling
- FTP & HTTP Cleartext Analysis
- TLS/SSL Decryption
- Credential Exposure
- Actionable Threat Intelligence
- Wireshark Investigation Workflow

---

# 💬 Key Takeaway

> "Anomalies leave traces at the packet level — from ARP poisoning to cleartext credentials. Knowing how to filter, decrypt, and correlate traffic turns raw packet captures into actionable security insights."

---

# 🚀 Next Steps

- Wireshark: Traffic Analysis Challenges
- Tcpdump
- Zeek
- Suricata
- NetworkMiner
- PCAP Malware Analysis
- Threat Hunting with Network Traffic
