# Endpoint-Threat-Detection-and-File-Integrity-Monitoring-using-Wazuh
# 🛡️ Automated Threat Detection & File Integrity Monitoring using Wazuh

<p align="center">

![Wazuh](https://img.shields.io/badge/Wazuh-XDR%20%7C%20SIEM-blue?style=for-the-badge&logo=wazuh)
![Ubuntu](https://img.shields.io/badge/Ubuntu-Linux-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-10-0078D6?style=for-the-badge&logo=windows)
![VirusTotal](https://img.shields.io/badge/VirusTotal-Threat%20Intelligence-394EFF?style=for-the-badge)
![MITRE ATT%26CK](https://img.shields.io/badge/MITRE-ATT%26CK-red?style=for-the-badge)
![Atomic Red Team](https://img.shields.io/badge/Atomic-Red%20Team-black?style=for-the-badge)
![Blue Team](https://img.shields.io/badge/Blue-Team-0052CC?style=for-the-badge)
![SOC](https://img.shields.io/badge/SOC-Incident%20Response-success?style=for-the-badge)

</p>

<p align="center">
  <strong>Enterprise SIEM • XDR • Endpoint Security • File Integrity Monitoring • Threat Intelligence • Automated Incident Response</strong>
</p>

---

# 📖 Project Overview

This project demonstrates the deployment and configuration of **Wazuh** as an **Extended Detection and Response (XDR)** and **Security Information and Event Management (SIEM)** platform for detecting, analyzing, and automatically responding to security threats across Linux and Windows endpoints.

A controlled virtual lab environment was built to simulate real-world attack scenarios using **Atomic Red Team**. Security events generated during attack simulations were collected by Wazuh agents, correlated by the Wazuh Manager, enriched with **VirusTotal** threat intelligence, mapped to the **MITRE ATT&CK Framework**, and automatically remediated using **Wazuh Active Response**.

This project demonstrates an end-to-end Blue Team workflow, from attack detection to automated incident response.

---

# 🎯 Objectives

- Deploy Wazuh as an enterprise SIEM and XDR platform
- Monitor Linux and Windows endpoints
- Implement File Integrity Monitoring (FIM)
- Detect unauthorized file modifications
- Integrate VirusTotal threat intelligence
- Configure automated malware remediation
- Simulate attacks using Atomic Red Team
- Analyze alerts mapped to the MITRE ATT&CK Framework
- Perform SOC-style incident investigation

---

# 🏗️ Lab Environment

| Component | Technology |
|-----------|------------|
| SIEM Platform | Wazuh |
| Wazuh Manager | Ubuntu Linux |
| Endpoint 1 | Ubuntu Linux |
| Endpoint 2 | Windows 10 |
| Threat Intelligence | VirusTotal |
| Attack Simulation | Atomic Red Team |
| Detection Framework | MITRE ATT&CK |
| Response | Wazuh Active Response |

---

# 🔄 Detection Workflow

(Place the workflow diagram here.)

---

# 🚀 Features Implemented

## 1. SIEM & XDR Deployment

- Centralized log collection
- Endpoint telemetry monitoring
- Security event correlation
- Rule-based threat detection
- Dashboard visualization

## 2. Endpoint Security Monitoring

- Process execution
- Authentication events
- File system activity
- Registry changes
- Security logs

## 3. File Integrity Monitoring (FIM)

- File creation detection
- File modification detection
- File deletion detection
- Integrity validation
- Real-time alerts

## 4. VirusTotal Integration

- File reputation lookup
- Malware verification
- Threat intelligence enrichment
- IOC validation

## 5. Automated Incident Response

- Automatic malware removal
- Threat containment
- Reduced response time
- Active Response automation

## 6. Attack Simulation

- Atomic Red Team attack emulation
- MITRE ATT&CK validation
- Detection testing
- Response verification

---

# 🛡️ MITRE ATT&CK Coverage

The project validates detections mapped to the MITRE ATT&CK Framework, including:

- Initial Access
- Execution
- Persistence
- Privilege Escalation
- Defense Evasion
- Credential Access
- Discovery
- Lateral Movement
- Collection

---

# 📊 Analysis & Results

- Successfully detected malicious file activity using File Integrity Monitoring (FIM)
- Verified suspicious files through VirusTotal threat intelligence
- Automated malware remediation using Wazuh Active Response
- Validated detections against MITRE ATT&CK techniques
- Correlated endpoint events across Linux and Windows systems
- Performed SOC-style investigation using the Wazuh Dashboard

---

# 

<img width="1536" height="1024" alt="wazuh" src="https://github.com/user-attachments/assets/7a1af18b-2c1e-4788-b168-30aa003bbd51" />


---

# 🛠️ Technologies Used

- Wazuh
- Ubuntu Linux
- Windows 10
- Atomic Red Team
- VirusTotal API
- MITRE ATT&CK Framework
- Elastic Stack
- Sysmon
- Linux Auditd
---

# ⚠️ Disclaimer

This project was developed in a controlled virtual laboratory environment for educational, research, and cybersecurity training purposes only. All attack simulations were performed on systems owned by the author. No production or third-party systems were targeted.

---
