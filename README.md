# AI Log Analyzer

> A lightweight cybersecurity tool that analyzes server log files, detects suspicious activity, and presents findings through a clean, interactive dashboard.

![Python](https://img.shields.io/badge/Python-3.11+-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)

---

## 📖 Overview

AI Log Analyzer is a web application designed to simplify log analysis for cybersecurity professionals, students, and homelab enthusiasts.

Instead of manually searching through thousands of log entries, users can upload a log file and instantly receive:

- Suspicious activity detection
- Failed login analysis
- Risk scoring
- Security recommendations
- AI-generated summaries

The goal is to reduce analysis time while providing meaningful insights into potential security events.

---

## ✨ Features

### Current

- Upload log files
- Parse Apache, SSH, and system logs
- Detect failed login attempts
- Count successful logins
- Identify suspicious IP addresses
- Generate a security risk score
- Interactive dashboard
- Dark mode interface

### Planned

- AI-generated incident summaries
- GeoIP visualization
- MITRE ATT&CK mapping
- PDF report generation
- JSON export
- Threat intelligence integration
- VirusTotal integration
- AbuseIPDB integration
- Sigma rule detection
- Live monitoring mode
- Email alerts
- Multi-user authentication

---

## 📂 Supported Log Types

- SSH Authentication Logs
- Apache Access Logs
- Apache Error Logs
- Nginx Logs
- Linux Syslog
- Windows Event Logs *(planned)*

---

## 🛠 Tech Stack

### Backend

- Python
- Flask
- Pandas
- Regex
- JSON

### Frontend

- HTML5
- CSS3
- JavaScript
- Chart.js

---

## 📊 Dashboard

The dashboard includes:

- System Overview
- Security Risk Score
- Failed Login Graphs
- Top Source IPs
- Suspicious Activity Timeline
- AI Incident Summary
- Recent Alerts

---

## 🚨 Detection Capabilities

The analyzer can identify:

- Brute-force attacks
- Password spraying
- Failed authentication attempts
- Repeated login failures
- Suspicious IP addresses
- High-volume requests
- Unauthorized access attempts
- Common attack patterns

---

## 📁 Project Structure

```
AI-Log-Analyzer/
│
├── app.py
├── requirements.txt
├── README.md
│
├── uploads/
│
├── templates/
│   ├── index.html
│   └── dashboard.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── analyzer/
│   ├── parser.py
│   ├── detector.py
│   ├── scoring.py
│   └── ai_summary.py
│
└── reports/
```

---

## 🚀 Installation

Clone the repository.

```bash
git clone https://github.com/yourusername/AI-Log-Analyzer.git
```

Navigate to the project directory.

```bash
cd AI-Log-Analyzer
```

Install dependencies.

```bash
pip install -r requirements.txt
```

Run the application.

```bash
python app.py
```

Open your browser.

```
http://127.0.0.1:5000
```

---

## 📈 Roadmap

- [x] Basic log parser
- [ ] Dashboard
- [ ] Risk scoring
- [ ] AI summaries
- [ ] GeoIP mapping
- [ ] Threat intelligence APIs
- [ ] Report exports
- [ ] Docker support
- [ ] Authentication
- [ ] Live monitoring

---

## 🤝 Contributing

Contributions, feature requests, and bug reports are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## ⚠ Disclaimer

This project is intended for educational purposes, cybersecurity research, and authorized defensive security operations only. Always obtain proper authorization before analyzing logs from systems you do not own or administer.

---

## 👤 Author

**Cohen**

Cybersecurity • Python • AI • Defensive Security

*"Turning raw logs into actionable security insights."*
