---
layout: default
title: Rodney Hall | Cybersecurity Portfolio
---

<style>
  .hero {
    text-align: center;
    padding: 2.5em 0 2em;
    border-bottom: 1px solid rgba(0,0,0,0.15);
    margin-bottom: 2em;
  }
  .hero h1 {
    font-size: 2em;
    margin-bottom: 0.2em;
    letter-spacing: 0.02em;
  }
  .hero .subtitle {
    color: #000;
    font-size: 0.95em;
    margin: 0.3em 0 1.4em;
    letter-spacing: 0.04em;
  }
  .btn-resume {
    display: inline-block;
    padding: 0.6em 1.6em;
    background: #2ea44f;
    color: #fff !important;
    border-radius: 5px;
    font-weight: 700;
    font-size: 0.92em;
    text-decoration: none !important;
    letter-spacing: 0.03em;
    transition: background 0.2s;
  }
  .btn-resume:hover { background: #2c974b; }
  .section-label {
    font-size: 0.7em;
    font-weight: 700;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: #e8661a;
    border-left: 3px solid #e8661a;
    padding-left: 0.65em;
    margin: 2.5em 0 1em;
  }
  .about-text {
    color: #000;
    font-size: 0.93em;
    line-height: 1.7;
    margin-bottom: 0;
  }
  .cert-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5em;
    padding: 0;
    margin: 0.8em 0 0;
    list-style: none;
  }
  .cert-grid li {
    background: rgba(0,0,0,0.04);
    border: 1px solid rgba(0,0,0,0.15);
    border-radius: 4px;
    padding: 0.3em 0.85em;
    font-size: 0.82em;
    color: #000;
  }
  .card {
    border: 1px solid rgba(0,0,0,0.15);
    border-radius: 6px;
    padding: 1.15em 1.4em;
    margin-bottom: 0.85em;
    background: rgba(0,0,0,0.02);
  }
  .card h3 {
    margin: 0 0 0.35em;
    font-size: 0.97em;
    font-weight: 700;
  }
  .card p {
    margin: 0 0 0.65em;
    color: #000;
    font-size: 0.88em;
    line-height: 1.6;
  }
  .card a.view-link {
    font-size: 0.85em;
    font-weight: 600;
    text-decoration: none;
    color: #0366d6;
  }
  .card a.view-link:hover { text-decoration: underline; }
  .card .in-progress {
    font-size: 0.72em;
    color: #555;
    font-weight: 400;
    margin-left: 0.5em;
  }
  .contact-row {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5em;
    margin-top: 0.8em;
    font-size: 0.88em;
  }
  .contact-row a { color: #0366d6; }
</style>

<div class="hero">
  <h1>Rodney Hall</h1>
  <p class="subtitle">SOC Analyst &nbsp;·&nbsp; Incident Triage &nbsp;·&nbsp; Threat Detection &nbsp;·&nbsp; Security Operations</p>
  <a class="btn-resume" href="https://raw.githubusercontent.com/rodney-hall/cybersecurity-portfolio/main/Rodney_Hall_Cybersecurity_Analyst_Resume.pdf" download>&#x2B07;&nbsp; Download Resume</a>
</div>

<p class="about-text">
I investigate threats, analyze logs, and build security controls across enterprise IT, cloud, and OT environments.
Targeting <strong>SOC Analyst Tier 1–2</strong>, Cybersecurity Analyst, and Information Security Analyst roles.
</p>

<div class="section-label">Certifications</div>

<ul class="cert-grid">
  <li>CompTIA Security+</li>
  <li>CompTIA Network+</li>
  <li>AWS Cloud Practitioner</li>
  <li>Microsoft AZ-900</li>
  <li>ICS-300 — CISA / DHS</li>
  <li>Google Cybersecurity Certificate</li>
</ul>

<div class="section-label">Projects</div>

<div class="card">
  <h3>SOC Operations &amp; Incident Triage</h3>
  <p>SIEM alert investigation, multi-source log correlation, IOC extraction, and end-to-end incident reporting mapped to MITRE ATT&amp;CK and NIST CSF.</p>
  <a class="view-link" href="https://rodney-hall.github.io/cybersecurity-portfolio/projects/google-cybersecurity-labs/">View Project &rarr;</a>
</div>

<div class="card">
  <h3>Active Directory Home Lab &mdash; Windows Server 2022</h3>
  <p>Built a domain controller from scratch, designed a multi-region OU structure across USA / Europe / Asia, and implemented least-privilege access controls at enterprise scale.</p>
  <a class="view-link" href="https://rodney-hall.github.io/cybersecurity-portfolio/projects/active-directory-home-lab/lab-01-ad-structure/">View Project &rarr;</a>
</div>

<div class="card">
  <h3>Azure Cloud Security &mdash; RBAC &amp; Least Privilege</h3>
  <p>Configured Azure RBAC and Entra ID, scoped Reader role assignments to a resource group, and validated least-privilege enforcement through documented access denial.</p>
  <a class="view-link" href="https://rodney-hall.github.io/cybersecurity-portfolio/projects/azure-cloud-security-labs/">View Project &rarr;</a>
</div>

<div class="card">
  <h3>Network Traffic Analysis &mdash; Wireshark / PCAP</h3>
  <p>Decoded BACnet and Modbus/TCP protocol traffic, correlated request-response sequences, and documented behavioral baselines for use in threat detection rule development.</p>
  <a class="view-link" href="https://rodney-hall.github.io/cybersecurity-portfolio/projects/ot-network-traffic-analysis/">View Project &rarr;</a>
</div>

<div class="section-label">OT / ICS Security &mdash; Specialization</div>

<div class="card">
  <h3>OT Network Threat Detection &amp; Incident Analysis</h3>
  <p>Identified unauthorized Modbus write commands and BACnet reconnaissance patterns in captured traffic. Documented IOCs and produced escalation recommendations for ICS environments.</p>
  <a class="view-link" href="https://rodney-hall.github.io/cybersecurity-portfolio/projects/ot-network-threat-detection/">View Project &rarr;</a>
</div>

<div class="card">
  <h3>OT/ICS Foundations &mdash; Purdue Model &amp; IT/OT Segmentation</h3>
  <p>Designed IT/OT segmentation architecture with an OT DMZ, mapped all five Purdue Model levels, and produced an analyst triage checklist for industrial environments.</p>
  <a class="view-link" href="https://rodney-hall.github.io/cybersecurity-portfolio/projects/ot-ics-foundations/">View Project &rarr;</a>
</div>

<div class="card">
  <h3>Linux System Baseline &mdash; OT Environment</h3>
  <p>Passive baseline audit of an OT-adjacent Linux system: enumerated services, listening ports, and network interfaces without impacting system availability.</p>
  <a class="view-link" href="https://rodney-hall.github.io/cybersecurity-portfolio/projects/ot-linux-baseline-lab/">View Project &rarr;</a>
</div>

<div class="card">
  <h3>BAS Security Playbook <span class="in-progress">In Progress</span></h3>
  <p>Incident response playbook for Building Automation Systems — 6 attack scenarios with IOCs, detection rules, SIEM integration, and response procedures for critical infrastructure.</p>
  <a class="view-link" href="https://rodney-hall.github.io/bas-security-playbook/" target="_blank" rel="noopener noreferrer">View Playbook &rarr;</a>
</div>

<div class="section-label">Contact</div>

<div class="contact-row">
  <span>&#x1F4C4; <a href="https://raw.githubusercontent.com/rodney-hall/cybersecurity-portfolio/main/Rodney_Hall_Cybersecurity_Analyst_Resume.pdf">Resume (PDF)</a></span>
  <span>&#x1F4BC; <a href="https://www.linkedin.com/in/hallrodney/">LinkedIn</a></span>
  <span>&#x2709;&#xFE0F; <a href="mailto:rodney7hall@gmail.com">rodney7hall@gmail.com</a></span>
</div>
