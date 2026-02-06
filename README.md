# Splunk SOC Dashboard


## Introduction
This project demonstrates the design and implementation of a SOC-style security monitoring dashboard using Splunk, focused on detecting and analyzing unauthorized authentication attempts against a Windows system.

To simulate real-world attack conditions, a Windows virtual machine was intentionally exposed to the internet, allowing organic attack traffic such as brute-force and password spraying attempts to occur. Windows Security Event logs were ingested into Splunk and analyzed from the perspective of a Tier-1/Tier-2 SOC analyst.

The purpose of this project is to showcase practical SIEM skills, realistic detection logic, and the ability to align findings with the MITRE ATT&CK framework.


## Objectives
- Simulate real-world credential-based attacks against a Windows system
- Collect and ingest Windows Security Event logs into Splunk
- Detect brute-force and password spray activity using SPL
- Build a SOC-relevant dashboard for monitoring and investigation
- Demonstrate investigative thinking


## Technologies and Tools Used
- SIEM Platform: Splunk Enterprise
- Operating System: Windows (Security Event Logs)
- Cloud Platform: Azure
- Key Event ID: 4625 – Failed Logon
- Query Language: Splunk Processing Language (SPL)


## Dashboard Design
The dashboard was structured to mirror how a real SOC monitors authentication-based threats, combining high-level metrics with analyst-driven investigation views.
### High-Level Monitoring Panels
