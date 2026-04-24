# Cybersecurity Operations & Threat Intelligence (COTI) – Attack Simulation & SIEM Detection

This project involves the development of a simulated enterprise security environment to analyse and detect cyberattacks. A vulnerable web application, OWASP Juice Shop, is used to emulate real-world attacks, while Wazuh is implemented to collect logs, detect threats, and automate responses. The project covers both offensive attack simulation and defensive monitoring.

---

## Project Overview

As cyber threats become increasingly sophisticated, organisations must adopt proactive monitoring and detection strategies. This project focuses on simulating common web and network attacks within a controlled lab environment and analysing them using a SIEM system.

The system collects logs from multiple sources, correlates events, and applies custom detection rules to identify malicious behaviour. It also demonstrates automated incident response to mitigate threats in real time.

---

## Business Requirements:

- **Threat Detection:** Identify malicious activities such as SQL injection, XSS, and brute-force attacks  
- **Log Monitoring:** Collect and analyse system and application logs for security events  
- **Incident Response:** Automatically respond to detected threats using active response mechanisms  

---

## Technologies Used:

- **Wazuh:** SIEM for log collection, correlation, and threat detection  
- **OWASP Juice Shop:** Vulnerable web application for attack simulation  
- **Kali Linux:** Attacker machine for penetration testing  
- **Windows Server:** Hosts the web application  
- **Ubuntu:** Hosts the Wazuh SIEM server  
- **Suricata:** IDS for network-level threat detection  

---

## Deliverables:

- **Environment Setup:** Virtual network with attacker, server, and SIEM integration  
- **Attack Simulation:** Execution of SQL injection, XSS, brute-force, malware, and privilege escalation attacks  
- **Log Analysis:** Collection and parsing of logs for threat detection  
- **Detection Engineering:** Development of custom SIEM rules for accurate alerting  
- **Mitigation:** Automated responses such as blocking IPs and removing malicious files  
