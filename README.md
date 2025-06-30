# Incident Report - ICMP Flood DDOS Attack
This repository contains an incident report for a simulated Distributed Denial of Service attack on a multimedia company. 
The goal of this report is to demonstrate my understanding of, and ability to report in according to, the NIST Cybersecurity Framework,
and its five core functions - Identify, Protect, Detect, Respond, Recover.

### Scenario Summary:
A multimedia company, offering multiple digital services, experiences a multi-hour outage due to a flood of ICMP (ping) packets. It was
determined to be a DDoS attack, launched through a misconfigured firewall allowing unrestricted ICMP traffic. 

The flood overwhelmed the internal network, causing internal systems/services to no longer respond. Normal traffic was effectively blocked.

Key findings & remediation steps were documented.

### Summary of Remediation:
- Improve firewall rules relating to incoming ICMP traffic
- Add source IP validation to identify spoofed packets
- Monitor network traffic for traffic pattern analysis
- Implement and configure an IDS system to flag abnormal ICMP behavior

