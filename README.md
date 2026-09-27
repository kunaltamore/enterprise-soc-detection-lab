# Enterprise SOC Detection & Incident Response Lab

## Overview

This project demonstrates a hands-on Security Operations Center (SOC) environment focused on security monitoring, threat detection, alert investigation, incident response, and MITRE ATT&CK mapping.

The lab uses Windows endpoint telemetry, Sysmon, Wazuh SIEM, and controlled security scenarios to simulate common enterprise security incidents.

## Objectives

- Monitor Windows security events
- Collect endpoint telemetry using Sysmon
- Analyze security alerts using Wazuh
- Investigate suspicious activities
- Create and test detection rules
- Map detected activities to MITRE ATT&CK
- Document incident investigation and response
- Build practical SOC analyst skills

## Lab Architecture

Windows Endpoint
→ Sysmon
→ Wazuh Agent
→ Wazuh Manager
→ Wazuh Dashboard
→ Detection
→ Investigation
→ Incident Response
→ MITRE ATT&CK Mapping

## Technologies

- Wazuh
- Sysmon
- Windows
- Linux
- Windows Event Logs
- MITRE ATT&CK
- Wireshark
- PowerShell
- Networking

## Detection Scenarios

The lab will include controlled simulations of:

1. Brute-force authentication attempts
2. Suspicious PowerShell activity
3. Unauthorized account creation
4. Suspicious process execution
5. Privilege escalation activity
6. Network reconnaissance

## Incident Response Process

Each detected incident will follow:

Detection → Triage → Investigation → Evidence Collection → MITRE Mapping → Containment Recommendation → Incident Report

## Disclaimer

All security testing in this project is performed in an isolated lab environment using systems owned or authorized for testing. No unauthorized systems are targeted.

## Project Status

🚧 In Progress
