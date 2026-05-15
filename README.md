# SIEM-Based-Cybersecurity-Monitoring-Lab
Built a cybersecurity lab using Wazuh, Kali Linux, and Windows for security monitoring and threat detection. Simulated brute-force attacks using Hydra and analyzed authentication logs through the SIEM dashboard. Monitored MITRE ATT&amp;CK alerts, audit failures, and malware simulation events using Wazuh
# SIEM-Based Cybersecurity Monitoring Lab

## Project Overview
This project demonstrates a cybersecurity home lab built using Wazuh, Kali Linux, and Windows. The lab was designed to simulate cyber attack scenarios and monitor security events through a SIEM dashboard.

## Lab Setup
- Wazuh Server VM (SIEM)
- Kali Linux VM (Attacker Machine)
- Windows 11 Host Machine (Victim Endpoint with Wazuh Agent)

## Technologies Used
- Wazuh SIEM
- Kali Linux
- Windows 11
- Hydra
- VirtualBox / VMware
- MITRE ATT&CK Framework

## Simulated Attacks
### 1. Brute-Force Attack Simulation
Performed login attempt simulations using Hydra from Kali Linux against the Windows machine. Authentication failures and related security events were monitored in the Wazuh dashboard.

### 2. Malware Simulation
Used the EICAR antivirus test file to simulate malware detection activity safely inside the lab environment.

### 3. File Integrity Monitoring
Modified and deleted test files to trigger file integrity monitoring alerts within Wazuh.

## Features Demonstrated
- Real-time security event monitoring
- Authentication failure detection
- MITRE ATT&CK mapping
- Endpoint monitoring using Wazuh agents
- Centralized log collection and analysis

## Screenshots
Add screenshots inside the `screenshots/` folder:
- Wazuh Dashboard
- Hydra Attack Terminal
- Security Alerts
- MITRE ATT&CK Events
- Agent Configuration

## Learning Outcomes
- Learned SIEM deployment and monitoring
- Understood log analysis and alert investigation
- Gained hands-on experience with cybersecurity attack simulation
- Worked with MITRE ATT&CK techniques and security event correlation

## Disclaimer
This project was performed in an isolated home lab environment for educational and defensive security purposes only.
