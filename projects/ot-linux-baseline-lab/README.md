# OT Linux Baseline & Service Visibility Lab

## Overview
This lab focuses on establishing a safe operational baseline for a Linux system in an OT-adjacent environment.  
The objective was to gain system visibility without impacting availability, following OT security best practices.

Rather than performing active exploitation, this lab emphasizes passive inspection, service awareness, and system health validation.

---

## Environment
- Platform: Ubuntu Linux (ARM64) running in UTM/QEMU
- Hostname: ot-lab
- Context: OT-adjacent Linux system requiring availability-first monitoring

---

## Objectives
- Verify system identity and configuration
- Observe running services and processes
- Establish a baseline of active system components
- Identify network exposure without intrusive scanning
- Practice OT-safe inspection techniques

---

## Actions Performed
- Configured and verified system hostname
- Validated OS and kernel information
- Monitored CPU and memory usage using `htop`
- Enumerated active services using `systemctl`
- Reviewed system state for operational readiness

---

## Key Takeaways
- OT environments prioritize availability over aggressive security testing
- Establishing a baseline is critical before detection or response
- Visibility into services and processes supports safe escalation decisions
- Passive inspection reduces risk to operational systems

---

## Screenshots
Screenshots documenting each phase of the lab are provided in the `/screenshots` directory.

---

## Skills Demonstrated
- Linux system administration
- OT security fundamentals
- Service and process visibility
- Availability-first security mindset
- Documentation and reporting
