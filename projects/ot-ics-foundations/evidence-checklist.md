# OT/ICS Incident Evidence Checklist (Foundational)

This checklist represents the basic evidence collection and documentation steps an analyst would follow during an OT-related security incident, with priority on safety and availability.

## Initial Triage
- Confirm affected environment (IT, OT, or boundary/DMZ)
- Identify impacted Purdue Model level(s)
- Determine if operations or safety are impacted
- Note time incident was detected and reported

## Asset Identification
- OT asset name or system (PLC, HMI, historian, jump server)
- Network segment (OT network, OT DMZ, IT network)
- IP address / hostname (if applicable)
- Criticality (high / medium / low)

## Network & Access Review
- Source and destination of suspicious traffic
- Protocol observed (e.g., Modbus, BACnet, TCP/IP)
- Authentication attempts or access paths
- Firewall or segmentation boundary involved

## Indicators of Concern
- Unexpected communication across IT/OT boundary
- Abnormal request frequency or function codes
- Unauthorized access attempts
- Changes that could impact availability or safety

## Documentation & Escalation
- Record findings in a ticket-style summary
- Attach diagrams, screenshots, or logs if available
- Escalate to OT/security leadership if availability or safety is at risk
- Preserve evidence and avoid making unapproved changes

## Analyst Notes
- OT incidents prioritize uptime and safety over immediate containment
- Changes to OT systems require approval and coordination
