## 🧪 Personal Home Lab Projects

These are cybersecurity simulations I personally designed and executed in my home lab to deepen my understanding of threat detection, log analysis, and incident response.

### 🔐 SSH Brute Force Attack + Fail2Ban Defense

**Objective:**  
Simulate a brute-force SSH attack using Hydra from Kali Linux against an Ubuntu target, analyze authentication logs, and deploy Fail2Ban to detect and prevent repeated failed login attempts.

**Steps Taken:**
- Configured VirtualBox host-only adapter for isolated Kali–Ubuntu communication
- Verified network connectivity between attacker and target
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
- Observed authentication failures and successful login attempts
- Parsed vsftpd logs for timestamps, IPs, and login activity
- Compiled findings into a structured incident report

**Outcome:**  
Gained hands-on experience in log analysis and incident documentation, reinforcing the importance of timely detection and structured reporting in cybersecurity operations.
