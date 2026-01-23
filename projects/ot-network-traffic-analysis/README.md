# OT Network Traffic Analysis (Wireshark)

## Overview
This project demonstrates hands-on analysis of Operational Technology (OT) network traffic using Wireshark. The focus is on identifying device discovery, control messages, and unencrypted communications commonly found in industrial control system (ICS) environments.

## Tools Used
- Wireshark
- Sample OT protocol PCAP files

## Protocols Analyzed
- BACnet (Building Automation and Control Networks)
- Modbus/TCP (Industrial Control Systems)

## Analysis Performed
- Applied protocol-specific display filters in Wireshark
- Identified broadcast and device discovery traffic (Who-Is / I-Am)
- Expanded and interpreted NPDU and APDU protocol fields
- Observed unencrypted OT communications
- Analyzed protocol behavior relevant to monitoring and incident detection

## Key Takeaways
- Many OT protocols operate without encryption or authentication
- Network visibility is critical for detecting unauthorized activity
- Wireshark is effective for baselining and investigating OT traffic

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

## Status
BACnet and Modbus/TCP analysis complete.
