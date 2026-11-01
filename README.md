# Hi, I'm Rakesh Rajbali 👋

Cybersecurity student at **St. John's University**, focused on **blue team / SOC analysis, threat hunting and incident response**. I build hands-on labs that turn raw security data (packets, logs, emails) into findings an analyst can act on, each mapped to **MITRE ATT&CK**.

## 🛡️ Security Labs

| Lab | What it does | Data source | Stack |
|---|---|---|---|
| [**Windows Event Log Hunter**](https://github.com/rakeshr9611-afk/windows-event-hunter) | Traces an RDP intrusion end-to-end: brute force → compromised logon → encoded PowerShell (auto-decoded) → service/task persistence → new admin → log clearing | Windows Security/System events | Python · PowerShell |
| [**SSH Auth Log Hunter**](https://github.com/rakeshr9611-afk/auth-log-hunter) | Correlates SSH brute force & password spraying with the successful login, sudo root shell and backdoor account that followed; builds an attack timeline | Linux `auth.log` | Python |
| [**PCAP Threat Hunter**](https://github.com/rakeshr9611-afk/pcap-threat-hunter) | Detects port scans, ICMP sweeps, DNS tunneling and cleartext credentials in packet captures | `.pcap` | Python · Scapy |
| [**Phishing Email Analyzer**](https://github.com/rakeshr9611-afk/phishing-email-analyzer) | Triages `.eml` files: SPF/DKIM/DMARC, lookalike domains, deceptive links, risky attachments → 0–100 risk score + IOCs | Email (`.eml`) | Python |
| [**Log Analyzer IDS**](https://github.com/rakeshr9611-afk/log-analyzer-ids) | Lightweight IDS for SSH brute force, user enumeration, SQLi/XSS/path traversal and web scanning | Server logs | Python |
| [**Password Strength Checker**](https://github.com/rakeshr9611-afk/password-strength-checker) | Rates password strength (entropy, patterns) and checks breaches via the HIBP k-anonymity API | User input | Python · API |

Every lab ships with a reproducible synthetic dataset, sample output, a written incident report and unit tests, and checks for **zero false positives** on benign activity.

## 🧰 Skills

**Detection & response:** threat hunting · log analysis (Linux, Windows, web) · network traffic analysis · phishing triage · MITRE ATT&CK mapping · incident timelines & reporting
**Tools & languages:** Python · Scapy · PowerShell · Wireshark · Git · pytest

## 📫 Contact

📧 rakeshr9611@gmail.com
