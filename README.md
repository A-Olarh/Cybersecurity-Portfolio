# 🛡️ Ayanloye Olaitan — Cybersecurity Portfolio

 Ayanloye Olaitan Cybersecurity Analyst | Threat Detection • Incident Response • Digital Forensics 
 Turning complex lab simulations into actionable security intelligence.

---

## 🎯 Summary

- Completed Google Cybersecurity Professional Certificate (Coursera,2025)
- Completed 100+ rooms on TryHackMe (SOC operations, penetration testing, incident response)
- Advanced to stage 2 of the 2025 WiCyS/SANS Cybersecurity Internship competition
- Designed and executed homelab environment simulating attacks and defensive responses.
- Hands-on projects simulating audits, threat modeling, and packet analysis
- Documenting technical learning through case studies and writeups,

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

### 🔐 SSH Brute Force Attack & Mitigation

**Scenario**: Detected and responded to SSH brute-force attack targeting Ubuntu server

**Attack Phase**:
- Launched 1,000+ login attempts using Hydra with common credential lists
- Monitored auth.log in real-time to observe attack patterns
- Documented time-to-compromise and successful authentication attempts

**Defense Phase**:
- Deployed Fail2Ban with custom jail configuration
- Set detection threshold: 5 failed attempts = 10-minute ban
- Validated mitigation through repeat attack simulation

**Key Findings**: 
- Default SSH configurations vulnerable to automated attacks
- Fail2Ban reduced attack surface by 95% within first 3 minutes
- Recommended: key-based authentication + rate limiting + geographic restrictions

📄 [View Full Case Study PDF](./Home_Lab_Projects/SSH_Brute_Force_Fail2Ban_Case_Study.pdf)

---

### 🚨 Multi-Vector Attack Simulation & Investigation

Simulated realistic attack chain:
1. Nmap reconnaissance scan
2. Exploited weak FTP credentials (Hydra)
3. Lateral movement attempt via SSH
4. Suspicious file upload to web directory

Then investigated as blue team:
- Correlated logs across multiple services (vsftpd, SSH, Apache)
- Reconstructed attack timeline using system logs
- Identified IOCs (source IPs, usernames, file hashes)
- Created detection rules in Fail2Ban + UFW
- Documented incident in NIST CSF format

Tools: Wireshark, Splunk, FTK Imager, Linux audit logs

---

## 🛠️ Technical Capabilities

**Threat Detection & Response**
- Log analysis and correlation (auth logs, syslog, vsftpd)
- SIEM tools: Splunk (queries, dashboards), Suricata (IDS rules)
- Packet analysis: Wireshark (PCAP filtering, protocol analysis), tcpdump

**Attack Simulation & Testing**
- Offensive tools: Hydra (brute force), Nmap (reconnaissance), Metasploit basics
- Defensive hardening: Fail2Ban, UFW, SSH key authentication
- Lab environments: Kali Linux, Ubuntu Server, VirtualBox

**Investigative Skills**
- Timeline reconstruction from system logs
- IOC identification and documentation
- Incident reporting following structured frameworks
- Basic scripting: Python (log parsing), Bash (automation)

---

## 📜 Certifications

- Google Cybersecurity Professional Certificate (Coursera, 2025)

🎓 Current Training
- TryHackMe: SOC Level 1 Learning Path (in progress)
- Let's Defend: Blue Team exercises and incident simulations
- Hack The Box: Offensive security fundamentals

---

🚀 Current Focus
- Building multi-system lab environment for DFIR practice
- Completing TryHackMe SOC Analyst pathway
- Documenting incident response procedures in personal playbook
- Studying for CompTIA Security+ (planned Q2 2026)

## 📫 Let's Connect

I'm actively seeking **entry-level SOC analyst or junior DFIR roles** where I can contribute to real security operations while learning from experienced practitioners.

Open to: Internships, volunteer SOC work, mentorship, cybersecurity collaborations

📧 Email: ayanloyeola@gmail.com  
🔗 LinkedIn: [linkedin.com/in/ayanloye-ola](https://www.linkedin.com/in/ayanloye-ola)  
📁 Portfolio Repo: [github.com/A-Olarh/Cybersecurity-Portfolio](https://github.com/A-Olarh/Cybersecurity-Portfolio)

---

## 🧭 About This Portfolio

This repository is a personalized documentation of my cybersecurity journey, combining coursework, homelab simulations, and real-world inspired projects. All content is original and reflects my hands-on learning and technical growth.

