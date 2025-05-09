# Pyramid of Pain

**Date Learned**: May 2025  
**Source**: TryHackMe – Blue Team Fundamentals  
**Category**: Threat Intelligence

## 🧱 What is the Pyramid of Pain?

A model that describes how difficult it is for an attacker to change certain indicators (IOCs) after detection:

- **Hash Values** – Easy to change
- **IP Addresses** – Easy to rotate
- **Domain Names** – A bit harder
- **Network/Host Artifacts** – Hard
- **TTPs (Tactics, Techniques, Procedures)** – Very hard

## 🧠 Takeaway:
- Defenders should focus on detecting TTPs, not just basic IOCs.
- Higher up the pyramid = more disruption to the attacker.

## 🔄 Next Step:
Document how tools like MITRE ATT&CK map to TTP detection.
