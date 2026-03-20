---
layout: default
title: SOC Operations & Incident Triage
---

← [Back to Portfolio](https://rodney-hall.github.io/cybersecurity-portfolio/)

# SOC Operations & Incident Triage

## Overview

Across four structured investigations, I analyzed logs from SSH, HTTP, and FTP services to detect brute-force attacks and unauthorized access, triaged SIEM alerts tied to phishing and malware campaigns, traced IOC patterns across multi-source log data, and delivered a full end-to-end incident report covering detection through recovery. A parallel security assessment mapped a fictional organization's control posture to the NIST Cybersecurity Framework and identified gaps requiring remediation. Each investigation produced structured documentation consistent with SOC Tier 1–2 analyst deliverables.

## Objective

Conduct log analysis, SIEM-based alert triage, and incident response investigations across multiple simulated attack scenarios to produce analyst-grade documentation and recommendations.

## Tools Used

- Elastic Stack (ELK) — Kibana dashboards and search queries
- Wireshark — packet-level traffic inspection
- SIEM platform — alert triage and correlation
- NIST Cybersecurity Framework — risk and control mapping
- MITRE ATT&CK — attack technique identification and mapping

---

## Lab 1 — Log Analysis & Threat Hunting

### What I Did

- Filtered and analyzed authentication, firewall, and system logs across HTTP, FTP, and SSH traffic
- Identified brute-force attack patterns through repeated failed authentication attempts from a single source IP
- Detected anomalous access sequences using Kibana queries and regex pattern matching
- Correlated log timestamps across sources to reconstruct the attacker's activity timeline

### Evidence / Findings

Log review surfaced repeated failed SSH login attempts from a single external IP, followed by a successful authentication — consistent with credential stuffing leading to unauthorized access. HTTP and FTP logs showed enumeration behavior prior to the successful login event.

### Outcome / Recommendations

- Flag repeated authentication failures from a single source as a high-priority alert condition
- Implement account lockout thresholds and SIEM alert rules for SSH brute-force indicators
- Correlate authentication logs with network session data to reduce false positive rates during triage

---

## Lab 2 — SIEM Investigation & IOC Extraction

### What I Did

- Investigated SIEM alerts tied to a phishing campaign with downstream malware execution
- Extracted IOCs from alert data including suspicious domains, source IPs, and file hashes
- Traced attacker lateral movement across multiple internal log sources
- Mapped observed techniques to MITRE ATT&CK: Initial Access (Phishing), Execution, Lateral Movement, Persistence
- Produced a structured incident report documenting detection, scope, containment actions, and escalation path

### Evidence / Findings

SIEM alerts correlated a phishing email delivery event with subsequent outbound connection attempts to an external C2 domain. Log data showed credential reuse across internal systems following initial compromise, consistent with lateral movement and privilege escalation attempts.

### Outcome / Recommendations

- Implement SIEM correlation rules to link email gateway alerts with outbound DNS and web proxy logs
- Tune alert thresholds to reduce alert fatigue while preserving detection of phishing-to-execution chains
- Tag SIEM alert playbooks with MITRE ATT&CK technique IDs for faster analyst classification during triage

---

## Lab 3 — Capstone: End-to-End Incident Investigation

### What I Did

- Received a simulated security incident with partial evidence and conducted the full investigation from initial detection through post-incident review
- Reviewed network logs, endpoint activity, and authentication records to reconstruct the full attack sequence
- Identified the attack vector, affected systems, and scope of compromise
- Documented each phase of the incident against the IR lifecycle: Preparation, Detection, Containment, Eradication, Recovery, Lessons Learned
- Delivered a complete incident report with technical findings and executive summary

### Evidence / Findings

Investigation identified an initial access event via phishing, followed by execution of a malicious payload, persistence mechanism installation via scheduled task, and lateral movement to a second internal host. The full attack chain mapped to the cyber kill chain from weaponization through actions on objectives.

### Outcome / Recommendations

- Establish detection coverage for persistence mechanisms including scheduled task creation and registry run key modifications
- Add endpoint telemetry to SIEM correlation rules to surface lateral movement earlier in the kill chain
- Conduct post-incident tabletop review to validate playbook coverage against the observed attack techniques

---

## Lab 4 — Security Assessment (NIST CSF)

### What I Did

- Reviewed policies, procedures, and control documentation for a fictional organization
- Identified threats to physical and digital assets including uncontrolled access, missing MFA, and inadequate patch cadence
- Mapped the organization's security posture across all five NIST CSF functions: Identify, Protect, Detect, Respond, Recover
- Delivered a written security assessment report with prioritized remediation recommendations

### Evidence / Findings

Assessment identified critical gaps in the Protect and Detect functions — no MFA enforcement on remote access paths, incomplete asset inventory, and no SIEM deployed. These gaps significantly reduced the organization's ability to detect and respond to active threats in a timely manner.

### Outcome / Recommendations

- Prioritize MFA deployment on all remote access pathways as an immediate risk reduction action
- Build a complete asset inventory as the foundation for all subsequent detection and response capabilities
- Implement a SIEM with baseline alerting before expanding to advanced detection use cases
- Assign NIST CSF function ownership to specific teams to drive accountability for gap remediation
