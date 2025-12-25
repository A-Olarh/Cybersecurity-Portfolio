<div align="center"> <h1> Ayanloye Olaitan</h1>
  <p><b>Cybersecurity Analyst | Threat Detection • Incident Response • Digital Forensics</b></p>
  <p><i> I’m Olaitan, a security analyst who sees cybersecurity from both sides of the battlefield. 
    With a foundation in blue team operations and a current focus on Digital Forensics Incident Response, I bring a layered, attacker-aware perspective to my role in threat detection and incident response.
    Currently, I transform lab-based simulations into technical security insights.</i></p>
</div>

---

## 🎯 Summary

- Completed 100+ rooms on TryHackMe (SOC operations, penetration testing, incident response) as a top 30% learner of 2025
- Advanced to stage 2 of the 2025 WiCyS/SANS Cybersecurity Internship competition with a 76% hit rate on the Sans.io ctf platform
- Designed and executed homelab environment simulating attacks and defensive responses.
- Hands-on projects simulating audits, threat modeling, and packet analysis
- Documenting technical learning through case studies and writeups,
- - Completed Google Cybersecurity Professional Certificate (Coursera,2025)

---

## 🧠 Cybersecurity Portfolio Projects

The table below reflects key areas of cybersecurity practice inspired by the Google Cybersecurity curriculum:

| Practicals | Toolkit |
| :--- | :--- |
| Conducting security audit for a mock organization | NIST, INFOSEC, CIA triad, risk management |
| Exploring Network security by securing network architecture | TCP/IP, firewalls, cloud networks |
| Command-line and database security using Linux & SQL | Bash, SQL injection, access control |
| Identifying and mitigating risks | Threat modeling, CVEs, asset inventory |
| Incident response detection and response focusing on playbooks | SOC workflows, escalation, containment |
| Packet analysis and traffic inspection using Tcpdump & Wireshark | PCAP, filters, network forensics |
| IDS/SIEM Monitoring and alerting | Suricata, Splunk, Chronicle |
| Automating security tasks | Python, log parsing, automation tools |

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
- LetsDefend: Blue Team exercises and incident simulations
- Hack The Box: Offensive security fundamentals

---

🚀 Current Focus
- Building multi-system lab environment for DFIR practice
- Completing TryHackMe SOC Analyst pathway
- Documenting incident response procedures in personal playbook
- Studying for CompTIA Security+ (planned Q1 2026)

## 📫 Let's Connect

I'm actively seeking **entry-level SOC analyst or junior DFIR roles** where I can contribute to real security operations while learning from experienced practitioners.

Open to: Internships, volunteer SOC work, mentorship, cybersecurity collaborations

📧 Email: ayanloyeola@gmail.com  
🔗 LinkedIn: [linkedin.com/in/ayanloye-ola](https://www.linkedin.com/in/ayanloye-ola)  
📁 Portfolio Repo: [github.com/A-Olarh/Cybersecurity-Portfolio](https://github.com/A-Olarh/Cybersecurity-Portfolio)

---

## 🧭 About This Portfolio

This repository is a personalized documentation of my cybersecurity journey, combining coursework, homelab simulations, and real-world inspired projects. All content is original and reflects my hands-on learning and technical growth.

