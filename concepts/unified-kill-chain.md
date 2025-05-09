# 🧩 Unified Kill Chain

**Date Learned**: May 2025  
**Category**: Threat Modeling & Attack Lifecycle  
**Source**: Self-study + TryHackMe (Advanced Blue Team)

---

## 🔍 What is the Unified Kill Chain?

The **Unified Kill Chain (UKC)** is an advanced threat modeling framework that combines:
- The **Lockheed Martin Cyber Kill Chain**, and  
- The **MITRE ATT&CK Framework**  

It provides a **comprehensive end-to-end model** of attacker behavior, from initial reconnaissance all the way to achieving objectives and persistence.

---

## 🔗 Structure of the Unified Kill Chain

The UKC includes **18 attack phases** across 3 stages:

### 🛠️ 1. **Initial Foothold**
- **Reconnaissance** – Gathering intel on the target (e.g., emails, open ports)
- **Weaponization** – Creating or preparing malware for delivery
- **Delivery** – Sending payloads via email, USB, websites, etc.
- **Social Engineering** – Tricking users (e.g., phishing, baiting) to enable access
- **Exploitation** – Exploiting a vulnerability to gain initial access

### 🧪 2. **Execution & Control**
- **Installation** – Installing malware or backdoors
- **Command & Control (C2)** – Establishing remote communication with the victim system
- **Credential Access** – Stealing or cracking usernames, passwords, tokens
- **Privilege Escalation** – Gaining higher-level access (e.g., from user to admin)
- **Lateral Movement** – Moving to other systems inside the network
- **Defense Evasion** – Hiding activity from antivirus, EDR, or logs

### 🎯 3. **Actions on Objectives**
- **Discovery** – Mapping out systems, users, and defenses
- **Collection** – Gathering sensitive data (e.g., files, credentials)
- **Exfiltration** – Sending stolen data out of the network
- **Impact** – Destroying, altering, or disrupting systems (e.g., ransomware)
- **Persistence** – Ensuring long-term access (e.g., creating accounts or startup scripts)
- **Cleanup** – Removing traces of the attack (e.g., deleting logs)


## 🎯 Why It Matters in DFIR

- **Gives defenders more context**: UKC links attacker behavior before and after exploitation.
- **Helps Blue Teams map alerts and logs** to actual attack stages.
- **Useful in forensic investigations** for tracing full attack lifecycle.
- Supports **defense-in-depth**: you can place controls at each stage.

---

## 🧠 Key Takeaways

- The UKC is **more comprehensive** than the original Cyber Kill Chain.
- It recognizes **post-compromise activity** and **behavioral techniques** from MITRE ATT&CK.
- It’s ideal for DFIR, threat hunting, and purple teaming.

---
