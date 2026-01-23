---
layout: default
title: OT Network Traffic Analysis (Wireshark)
---

# OT Network Traffic Analysis (Wireshark)

Hands-on analysis of Operational Technology (OT) and Industrial Control System (ICS) network traffic using Wireshark. This project focuses on identifying device discovery behavior, control messages, and protocol-level communication patterns commonly found in industrial environments.

---

## Tools Used
- Wireshark
- Sample OT/ICS PCAP files

---

## Protocols Analyzed
- **BACnet** (Building Automation and Control Networks)
- **Modbus/TCP** (Industrial Control Systems)

---

## Analysis Performed
- Applied protocol-specific display filters in Wireshark  
- Identified broadcast-based device discovery traffic (Who-Is / I-Am)  
- Expanded and interpreted NPDU and APDU fields  
- Observed Modbus request/response patterns and function codes  
- Documented unencrypted OT protocol behavior

---

## Evidence

### BACnet Analysis

**Filtered BACnet traffic**  
![BACnet Filter](./bacnet-filter-applied.png)

**NPDU / APDU expansion**  
![BACnet NPDU APDU](./bacnet-npdu-apdu-expanded.png)

**APDU / NPDU breakdown**  
![BACnet Breakdown](./bacnet-apdu-npdu-breakdown.png)

### Modbus/TCP Analysis

**Filtered Modbus traffic**  
![Modbus Filter Applied](./modbus-filter-applied.png)

**Function code inspection**  
![Modbus Function Code](./modbus-function-code.png)

**Request / response correlation**  
![Modbus Request Response](./modbus-request-response.png)
