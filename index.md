# Cybersecurity Portfolio — Rodney Hall

This repository supports my public cybersecurity portfolio and documents hands-on security projects focused on protecting availability, safety, and visibility across IT and OT environments. My work emphasizes OT/ICS monitoring, incident analysis, and secure system baselining using non-intrusive, operations-aware techniques.

---

## Professional Focus
- OT / IT security monitoring and visibility  
- Incident detection, triage, and escalation in mixed IT/OT environments  
- OT network traffic analysis and protocol inspection  
- Secure system baselining (Linux & Windows)  
- Identity and access management (Active Directory, Azure Entra ID)  
- IT/OT segmentation aligned to the Purdue Model  
- Cloud security fundamentals (Azure & AWS)

---

## Featured Projects (Hands-On)

### OT/ICS Foundations Mini-Lab (Purdue Model & IT/OT Segmentation)
Demonstrates how enterprise IT and operational technology (OT) environments are segmented to preserve safety, uptime, and operational integrity.
- Designed IT ↔ OT segmentation with an OT DMZ
- Applied Purdue Model concepts (Levels 0–5)
- Developed an OT incident evidence checklist to support escalation and response

**Project:** [OT/ICS Foundations Mini-Lab](projects/ot-ics-foundations/)

---

### OT Linux Baseline & Service Visibility Lab
Established a secure operational baseline for a Linux system in an OT-adjacent environment using availability-first, non-intrusive inspection methods.
- Verified system identity and baseline health
- Enumerated running services and processes
- Identified listening network ports without active scanning
- Applied OT security principles prioritizing stability and uptime

**Project:** [OT Linux Baseline & Visibility Lab](projects/ot-linux-baseline-lab/)

---

### OT Network Traffic Analysis (Wireshark)
Performed hands-on analysis of OT/ICS network traffic to understand protocol behavior and device communication.
- Analyzed BACnet traffic including device discovery and NPDU/APDU inspection
- Analyzed Modbus/TCP traffic, function codes, and request/response behavior
- Applied protocol-specific display filters to isolate relevant traffic
- Correlated Modbus requests and responses to validate command execution

**Project:** [OT Network Traffic Analysis (Wireshark)](projects/ot-network-traffic-analysis/)

---

### OT Network Threat Detection & Incident Analysis
Simulated detection and investigation of suspicious OT network activity using an incident-response mindset.
- Identified potentially unsafe Modbus control behavior
- Evaluated BACnet discovery traffic for reconnaissance indicators
- Documented findings with mitigation recommendations tailored to OT environments

**Project:** [OT Network Threat Detection & Incident Analysis](projects/ot-network-threat-detection/)

---

### Active Directory Home Lab (Windows Server 2022)
Built and structured a Windows domain lab to practice enterprise identity management and access control.
- Promoted Windows Server 2022 to **Domain Controller** (AD DS + DNS)
- Designed a multi-region OU structure (**USA / Europe / Asia**)
- Created Users, Computers, and Servers containers per region
- Implemented departmental OUs (**IT, HR, Accounting, Sales, Management**)
- Created users, security groups, and computer/server objects using realistic enterprise naming

**Lab Write-Up:** [AD OU Structure + Objects](projects/active-directory-home-lab/lab-01-ad-structure/README.md)

---

## Labs & Practical Experience

### Google Cybersecurity Certificate — Hands-On Labs
Applied core security concepts through structured labs and investigations.
- Log analysis and alert investigation
- SIEM-style incident triage and response workflows
- Risk assessment and threat modeling
- Linux security fundamentals
- SQL queries for security investigations
- Introductory Python for automation

---

### Azure Cloud Security Labs
Hands-on Azure security labs focused on identity, access control, and least-privilege enforcement.
- Azure RBAC (role-based access control)
- Microsoft Entra ID (Azure AD) fundamentals
- Least-privilege validation and access denial testing
- Cloud security fundamentals with audit-ready documentation

**Project:** [Azure Cloud Security Labs](projects/azure-cloud-security-labs/)

---

## Training & Continuous Practice
- TryHackMe profile: [tryhackme.com/p/rodney7hall](https://tryhackme.com/p/rodney7hall)

---

## Certifications
- CompTIA Security+  
- AWS Certified Cloud Practitioner  
- Microsoft AZ-900  
- Microsoft AZ-500  
- Industrial Control System Cybersecurity (ICS-300) – CISA / DHS  
- Google Cybersecurity Certificate  

---

## Resume & Contact
- **Resume (PDF):** https://raw.githubusercontent.com/rodney-hall/cybersecurity-portfolio/main/Rodney%20Hall%20Resume%202026.pdf
- **LinkedIn:** [linkedin.com/in/hallrodney](https://www.linkedin.com/in/hallrodney/)
- **Email:** [rodney7hall@gmail.com](mailto:rodney7hall@gmail.com)
