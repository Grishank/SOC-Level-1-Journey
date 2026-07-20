# 🏔️ Summit — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/Summit-banner.png?raw=true" alt="Summit Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1  
**Module:** Cyber Defence Frameworks  
**Difficulty:** Medium  
**Room Link:** https://tryhackme.com/room/summit  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

**Summit** is a practical capstone challenge that combines knowledge from the **Pyramid of Pain** and **MITRE ATT&CK** rooms. Acting as a Blue Team analyst, you configure security detections to identify and block increasingly sophisticated malware samples while forcing the adversary to change more costly Indicators of Compromise (IOCs).

The room focuses on:
- Practical malware detection
- Detection engineering
- Pyramid of Pain application
- Blue Team defensive strategy
- MITRE ATT&CK concepts

---

# 🎯 Learning Objectives

- Apply the Pyramid of Pain in a real scenario
- Configure detections for different IOCs
- Stop malware execution through layered defenses
- Understand the increasing cost imposed on attackers
- Practice Blue Team detection engineering

---

# 📌 Task 1 — Summit Challenge

Worked through an interactive detection engineering lab where five malware samples were executed sequentially.

For each stage, security controls were configured to detect increasingly difficult attacker indicators:

- Hash detection
- IP address detection
- Domain detection
- Host artifacts
- Network artifacts

Successfully detected and blocked every malware sample while progressing higher on the Pyramid of Pain.

---

# 🛡️ Detection Progression

| Stage | Detection Focus |
|--------|-----------------|
| Sample 1 | File Hash |
| Sample 2 | IP Address |
| Sample 3 | Domain Name |
| Sample 4 | Host Artifacts |
| Sample 5 | Network Artifacts |

Each new detection forced the attacker to invest more effort to evade security controls.

---

# 🎯 Final Objective

Completed the challenge by successfully preventing all simulated attacks and obtaining the final flag after defeating the adversary's campaign.

This demonstrated how layered detections significantly increase attacker cost and improve organizational security.

---

# 🔍 Key Concepts Learned

- Detection Engineering
- Practical Blue Team Operations
- Pyramid of Pain
- Malware Detection
- IOC-Based Detection
- Defense in Depth
- Threat Detection Strategy

---

# 💬 Key Takeaway

> “The best detections don't simply catch malware—they force attackers to completely change how they operate.”

---

# 🚀 Next Steps

- Build Sigma detection rules
- Practice SIEM alert creation
- Explore YARA rule development
- Study MITRE ATT&CK detections
- Continue advanced Blue Team labs
