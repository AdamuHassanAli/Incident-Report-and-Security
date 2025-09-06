
## 📖 Incident Report and Security Improvement Plan using NIST Cybersecurity Framework (CSF)

---

# 📌 Portfolio Project Summary
As a cybersecurity analyst for a multimedia company offering web design, graphic design, and social media marketing solutions, I conducted an incident analysis after the organization experienced a **Distributed Denial of Service (DDoS) attack**.  
The attack involved a **flood of ICMP packets** that disrupted internal network services for two hours.  
This project required me to apply the **NIST Cybersecurity Framework (CSF)** to document the incident, identify vulnerabilities, and develop a plan to strengthen the organization’s security posture.

---

## ⚠️ What Happened
- The attacker exploited an **unconfigured firewall**, allowing a flood of ICMP pings to overwhelm the network.  
- Internal network traffic and services became unavailable.  
- The incident response team blocked incoming ICMP packets, took non-critical services offline, and restored critical services.  
- Post-incident, the team implemented:  
  - Firewall rules to limit ICMP packets  
  - Source IP verification  
  - IDS/IPS deployment  
  - Network monitoring solutions  

---

## 🔎 How I Applied the NIST CSF

### 🟦 Identify
- Conducted an asset inventory to determine affected systems (firewall, servers, applications).  
- Identified business processes impacted (client-facing design and social media services).  
- Determined the root cause: **improper firewall configuration**.  

### 🟩 Protect
- Recommended firewall hardening and ICMP rate-limiting.  
- Suggested **staff training** on network monitoring and attack indicators.  
- Updated policies requiring **periodic firewall audits** and patching.  

### 🟨 Detect
- Proposed integrating a **SIEM solution** for anomaly detection.  
- Implemented continuous monitoring to identify DDoS-like behavior.  
- Configured IDS/IPS systems to flag suspicious ICMP packets.  

### 🟥 Respond
- Developed a **DDoS incident response playbook**.  
- Improved communication protocols between IT staff, management, and end users.  
- Documented the incident and mapped it to **MITRE ATT&CK techniques**.  

### 🟪 Recover
- Outlined recovery steps: system restoration, firewall validation, and service resumption.  
- Recommended **tabletop exercises** for incident response rehearsal.  
- Enhanced **business continuity documentation** to reduce downtime in future incidents.  

---

## ✅ Outcome
This project strengthened the company’s ability to **detect, respond, and recover** from network-based threats.  
By leveraging the **NIST CSF**, I:  
- Demonstrated a structured approach to incident handling.  
- Improved transparency and communication with stakeholders.  
- Recommended **technical and procedural improvements** that enhanced organizational resilience against DDoS attacks.  

---
