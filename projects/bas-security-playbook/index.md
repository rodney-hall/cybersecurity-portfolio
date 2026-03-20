---
layout: default
title: BAS Security Playbook
---

← [Back to Portfolio](https://rodney-hall.github.io/cybersecurity-portfolio/)

# BAS Security Playbook

**Security monitoring and incident response for Building Automation Systems in defense and critical infrastructure environments.**

> **Status:** Work in Progress — actively developing based on ICS-300 training, hands-on OT labs, and industry standards (IEC 62443, NIST SP 800-82).

---

## Overview

This playbook documents security monitoring and incident response procedures for Building Automation Systems (BAS) in defense and critical infrastructure environments. BAS networks control HVAC, lighting, access control, and fire safety systems — all availability-critical, all historically under-secured. The playbook focuses on protecting these systems using passive, non-intrusive methods that preserve operational continuity and life safety.

## Objective

Provide a structured, analyst-ready reference for detecting, investigating, and responding to security incidents in BAS environments, with controls and procedures appropriate for systems where availability and safety take precedence over aggressive security posture.

## Scope

- BAS network architecture and Purdue Model alignment
- Common threat scenarios specific to building automation
- Detection strategies using passive OT network monitoring
- Incident response procedures prioritizing operational continuity

## Target Audience

- OT Security Analysts
- Building Operations Teams
- Facility Security Managers
- Defense Property Security Personnel

## Key Principles

1. **Availability First** — BAS systems control life safety. Security controls must not disrupt operations.
2. **Passive Monitoring** — Use non-intrusive detection methods to avoid impacting real-time control systems.
3. **Defense in Depth** — Layer security controls across network, application, and physical domains.
4. **Operational Awareness** — Understand business impact before implementing any security change.

---

## Playbook Sections

### 1. BAS Architecture Overview
BAS network design, Purdue Model mapping, protocol landscape (BACnet, Modbus, LonWorks), and IT/OT segmentation architecture for defense properties.

### 2. Common Threats & Attack Scenarios
Threat landscape specific to building automation — reconnaissance via BACnet discovery, unauthorized setpoint manipulation, HVAC disruption, and MITRE ATT&CK correlation for ICS.

### 3. Monitoring & Detection Strategies
How to detect anomalies without disrupting operations — passive Wireshark captures, BACnet/Modbus baseline deviation alerts, Wireshark filters, and SIEM integration guidance.

### 4. Incident Response Procedures
Step-by-step response playbook for BAS security incidents, prioritizing life safety and operational continuity throughout detection, containment, eradication, and recovery phases.

---

## Technologies & Standards

- **Protocols:** BACnet/IP, Modbus TCP, LonWorks
- **Tools:** Wireshark, SIEM
- **Frameworks:** Purdue Model, MITRE ATT&CK for ICS
- **Standards:** IEC 62443, NIST SP 800-82, ASHRAE 135

---

## Author

Rodney Hall — ICS-300 (CISA/DHS) | CompTIA Security+ | CompTIA Network+
[LinkedIn](https://www.linkedin.com/in/hallrodney/) | [Portfolio](https://rodney-hall.github.io/cybersecurity-portfolio/)
