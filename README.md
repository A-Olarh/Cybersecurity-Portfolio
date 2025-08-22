# 🛡️ Ayanloye Olaitan — Cybersecurity Portfolio

Welcome to my cybersecurity portfolio! I'm Ayanloye, a cybersecurity analyst-in-training with hands-on experience in threat detection, incident response, and log analysis. This portfolio showcases my learning journey through the **Google Cybersecurity Professional Certificate** and personal homelab simulations designed to mirror real-world attack scenarios.

---

## 🎯 Summary

- Completed Google Cybersecurity Professional Certificate (Coursera)
- Built hands-on projects simulating audits, threat modeling, and packet analysis
- Designed and executed personal homelab simulations using Kali Linux, Ubuntu, Hydra, Fail2Ban, and vsftpd
- Passionate about ethical hacking, digital forensics, and automation

---

## 🧠 Cybersecurity Portfolio Projects

These projects reflect key areas of cybersecurity practice inspired by the Google Cybersecurity curriculum:

| Module | Description | Skills Gained |
| :--- | :--- | :--- |
| Conduct an Audit | Security audit of a mock organization | NIST, INFOSEC, CIA triad, risk management |
| Network Security | Securing network architecture | TCP/IP, firewalls, cloud networks |
| Linux & SQL | Command-line and database security | Bash, SQL injection, access control |
| Threats & Vulnerabilities | Identifying and mitigating risks | Threat modeling, CVEs, asset inventory |
| Detection & Response | Incident response playbooks | SOC workflows, escalation, containment |
| Tcpdump & Wireshark | Packet analysis and traffic inspection | PCAP, filters, network forensics |
| IDS & SIEM | Monitoring and alerting | Suricata, Splunk, Chronicle |
| Automation with Python | Scripting for security tasks | Python, log parsing, automation tools |

---

## 🧪 Personal Home Lab Projects

These are cybersecurity simulations I personally designed and executed in my home lab to deepen my understanding of threat detection, log analysis, and incident response.

### 🔐 SSH Brute Force Attack + Fail2Ban Defense

**Objective:**  
Simulate a brute-force SSH attack using Hydra from Kali Linux against an Ubuntu target, analyze authentication logs, and deploy Fail2Ban to detect and prevent repeated failed login attempts.

**Steps Taken:**
- Configured VirtualBox host-only adapter for isolated Kali–Ubuntu communication  
- Launched brute-force SSH attack using Hydra  
- Captured failed login attempts in `/var/log/auth.log`  
- Installed and configured Fail2Ban to monitor SSH logs  
- Verified IP banning of attacker after repeated failures

**Outcome:**  
Demonstrated how attackers exploit weak credentials and how Fail2Ban can dynamically detect and block malicious IPs using log-based intrusion prevention.

---

### 📁 FTP Brute Force Attack + Log Analysis

**Objective:**  
Simulate and analyze an FTP brute-force attack using Hydra, review vsftpd logs for intrusion detection, and document the incident using a structured reporting format.

**Steps Taken:**
- Installed and configured `vsftpd` on Ubuntu  
- Created test FTP users and enabled login configurations  
- Launched brute-force attempts from Kali Linux using Hydra  
- Parsed vsftpd logs for timestamps, IPs, and login activity  
- Compiled findings into a structured incident report

**Outcome:**  
Gained hands-on experience in log analysis and incident documentation, reinforcing the importance of timely detection and structured reporting in cybersecurity operations.

---

## 🛠️ Skills & Tools

- **Networking:** TCP/IP, OSI, DNS, VPN  
- **Tools:** Wireshark, Nmap, Hydra, Fail2Ban, Suricata, Splunk  
- **Languages:** Python, Bash  
- **Platforms:** Linux (Ubuntu), Kali Linux, GitHub  
- **Concepts:** Risk management, incident response, vulnerability scanning, log analysis

---

## 📜 Certifications

- Google Cybersecurity Professional Certificate (Coursera, July 2025)
- Additional modules in progress: Security Operations, SIEM, Threat Intelligence

---

## 📫 Contact

Let’s connect or collaborate:  
📧 Email: ayanloyeola@gmail.com  
🔗 LinkedIn: [linkedin.com/in/ayanloye-ola](https://www.linkedin.com/in/ayanloye-ola)  
📁 Portfolio Repo: [github.com/A-Olarh/Cybersecurity-Portfolio](https://github.com/A-Olarh/Cybersecurity-Portfolio)

---

## 🧭 About This Portfolio

This repository is a personalized documentation of my cybersecurity journey, combining coursework, homelab simulations, and real-world inspired projects. All content is original and reflects my hands-on learning and technical growth.

