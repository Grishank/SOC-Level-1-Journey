# 🚨 SOC L1 Alert Triage — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/SOC-Level-1-Journey/blob/main/assets/SOC-L1-Alert-Triage-banner.png?raw=true" alt="SOC L1 Alert Triage Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** SOC Level 1  
**Module:** SOC Team Internals  
**Difficulty:** Easy  
**Room Link:** https://tryhackme.com/room/socl1alerttriage  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

This room introduces the fundamentals of SOC alert triage and explains how analysts investigate, prioritize, and respond to security alerts efficiently.

The room focuses on:
- Security events and alerts
- Alert properties
- Alert prioritization
- Triage workflows
- SOC investigation process

---

# 🎯 Learning Objectives

- Understand the difference between events and alerts
- Learn important alert properties
- Understand alert prioritization
- Learn SOC triage workflow
- Understand investigation processes

---

# 📌 Task 1 — Introduction

Learned how SOC analysts handle large numbers of alerts daily and follow structured workflows to investigate suspicious activity efficiently.

---

# 📡 Task 2 — Events and Alerts

## Event
An event is any observable activity in a system or network.

Examples:
- User login
- File download
- Process execution
- Network connection

## Alert
An alert is generated when suspicious or malicious activity is detected.

Examples:
- Multiple failed logins
- Malware detection
- Privilege escalation attempt
- Suspicious outbound traffic

---

# 🧾 Task 3 — Alert Properties

Important alert details:
- Severity
- Source IP
- Destination IP
- Timestamp
- Username
- Triggered rule
- Affected host

These properties help analysts understand the scope and impact of suspicious activity.

---

# ⚠️ Task 4 — Alert Prioritisation

SOC analysts prioritize alerts based on:
- Severity level
- Business impact
- Threat confidence
- Critical systems affected
- Potential damage

## Common Severity Levels

| Severity | Meaning |
|---|---|
| Low | Minor suspicious activity |
| Medium | Requires investigation |
| High | Serious threat detected |
| Critical | Immediate response needed |

---

# 🔍 Task 5 — Alert Triage

Basic SOC triage workflow:

```text
Receive Alert → Validate Activity → Investigate Evidence → Determine Impact → Escalate or Close
```

SOC analysts must identify:
- False positives
- True positives
- Malicious indicators
- Impacted systems
- Required response actions

---

# 🔑 Key Concepts Learned

- Events vs alerts
- Alert investigation
- Alert prioritization
- SOC workflows
- Threat validation
- Security monitoring basics

---

# 💬 Key Takeaway

> “Effective alert triage helps SOC analysts quickly identify real threats while reducing investigation time and false positives.”

---

# 🚀 Next Steps

- Practice SIEM investigations
- Learn log analysis
- Explore threat hunting
- Study incident response workflows
- Build SOC investigation projects
