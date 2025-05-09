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

### 🛠️ 1. **Initial Foothold (Preparation & Delivery)**
- Reconnaissance  
- Weaponization  
- Delivery  
- Social Engineering  
- Exploitation  

### 🧪 2. **Execution & Control**
- Installation  
- Command & Control (C2)  
- Credential Access  
- Privilege Escalation  
- Lateral Movement  
- Defense Evasion  

### 🎯 3. **Actions on Objectives**
- Discovery  
- Collection  
- Exfiltration  
- Impact  
- Persistence  
- Cleanup  

---

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
