# Cybersecurity Incident Handling & Network Monitoring Portfolio

> **Project Context:** Google Cybersecurity Professional Certificate

<div align="center">

  ![Google](https://img.shields.io/badge/Google-Cybersecurity-4285F4?style=for-the-badge&logo=google&logoColor=white)
  ![Incident Response](https://img.shields.io/badge/Incident-Response-E01E5A?style=for-the-badge&logo=fireeye&logoColor=white)
  ![Network Security](https://img.shields.io/badge/Network-Security-00BFFF?style=for-the-badge&logo=wireshark&logoColor=white)
  ![Threat Intel](https://img.shields.io/badge/Threat-Intelligence-FFD700?style=for-the-badge&logo=virustotal&logoColor=black)

</div>

---

## Project Overview

This repository serves as a comprehensive professional journal documenting various cybersecurity incidents, technical investigations, and tool-based analyses. From mitigating ransomware attacks in healthcare to monitoring real-time network traffic with IDS tools, these entries demonstrate a structured lifecycle approach to **Detection, Analysis, and Remediation**.

The documentation follows industry-standard frameworks, including the **5 W's** and structured **Incident Response Playbooks**, to ensure technical accuracy and organizational consistency.

---

## Cybersecurity Toolkit & Applications

The following tools and methodologies were applied across various simulation scenarios to detect threats and analyze system vulnerabilities.

### 1. Network Analysis & Monitoring
* **Wireshark (GUI):** Performed Deep Packet Inspection (DPI) to identify protocol anomalies and detect unencrypted sensitive data within network streams.
* **tcpdump (CLI):** Executed real-time packet interception in command-line environments, focusing on efficient data collection for later forensic analysis.
* **Suricata (IDS/IPS):** Configured custom intrusion detection rules to trigger alerts on specific network patterns (e.g., "GET on wire") and analyzed `eve.json` telemetry.
* **jq:** Utilized this powerful JSON processor to filter and correlate complex event data from Suricata logs, enabling precise threat hunting.

### 2. Threat Intelligence & Investigation
* **VirusTotal:** Leveraged cloud-based intelligence to perform static analysis of suspicious file hashes (SHA-256), identifying Indicators of Compromise (IoCs) and confirmed malware.
* **Phishing Playbooks:** Followed standardized SOC procedures to triage alerts, evaluate sender/receiver inconsistencies, and execute proper escalation paths.
* **Log Analysis:** Audited Web Application and Server logs to identify patterns of **Forced Browsing** and unauthorized data exfiltration.

---

## Featured Case Study: Ransomware Response

| Category | Details |
| :--- | :--- |
| **Scenario** | A U.S. health clinic experienced a total shutdown due to encrypted medical records. |
| **Attack Vector** | Targeted phishing emails tricking employees into executing a malicious attachment. |
| **Analysis** | Documented via the 5 W's to identify the unethical hacker group and the financial extortion motive. |
| **Mitigation** | Proposed the implementation of advanced email filtering, EDR solutions, and offline backup redundancy. |

---

## Technical Takeaways

* **Structured Lifecycle:** Transitioned from viewing security as isolated events to a structured lifecycle of detection, analysis, and remediation.
* **The Power of Documentation:** Standardized journals and playbooks are vital for maintaining team consistency and legal compliance during high-pressure breaches.
* **Protocol Mastery:** Deep packet inspection (DPI) is a fundamental skill for verifying whether data is moving securely or if a Man-in-the-Middle (MITM) attack is in progress.
* **Vulnerability Proactivity:** Identifying flaws like "Forced Browsing" through log analysis underscores the importance of routine penetration testing and strict URL allowlisting.

---

## Personal Reflection

> "I've learned that effective incident response is a balance between technical tool mastery and disciplined documentation. Whether I'm debugging a Suricata rule or analyzing a PII breach, the goal remains the same: minimizing impact and hardening defenses for the future."

---

<div align="center">
  <sub><i>Disclaimer: This is a fictional case study portfolio completed for educational purposes as part of the Google Cybersecurity Certificate.</i></sub>
</div>
