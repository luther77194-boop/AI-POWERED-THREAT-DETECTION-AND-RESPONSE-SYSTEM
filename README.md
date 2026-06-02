# 🚨 TDRS - AI Powered Threat Detection and Response System

## 🔐 Overview
TDRS (Threat Detection and Response System) is an AI-powered Security Operations Center (SOC) platform designed to detect, analyze, and respond to cyber threats in real time. It simulates real-world SOC operations by combining attack detection, incident management, and automated response mechanisms into a single unified system.

The system focuses on behavior-based detection rather than static rules, making it effective against modern distributed attacks such as DDoS. It provides a complete SOC workflow from detection to mitigation.

---

## 🎯 Problem Statement
Cyber attacks such as DDoS, Brute Force, and SQL Injection are rapidly increasing, while traditional systems are reactive and lack real-time response capabilities. There is a need for an intelligent system that can detect threats, manage incidents, and assist in automated response.

---

## ⚙️ Features

- 🔍 Real-time attack detection (DDoS, Brute Force, SQL Injection)
- 📊 Live SOC dashboard for monitoring threats
- 🚨 Automated incident creation and tracking
- 👨‍💻 Analyst-driven incident management (assign, investigate, respond)
- 🛡️ Automated and manual response system
- 📌 MITRE ATT&CK mapping and risk scoring
- 🌍 IP-based enrichment and threat intelligence
- 🧠 Behavior-based detection (not just IP blocking)

---

## 🧠 System Architecture
  Traffic → Detection Engine → Threat Analysis → Incident Creation → SOC Dashboard → Analyst → Response Engine → Mitigation


---

## 🔄 SOC Workflow
  Attack → Detection → Analysis → Incident → Response → Monitoring


---

## 🛠️ Tech Stack

- **Backend:** Python (Flask)
- **Database:** SQLite
- **Network Monitoring:** Scapy
- **Frontend:** HTML, Tailwind CSS, JavaScript
- **Architecture:** REST API-based SOC system

---

## 🚀 Installation & Setup

```bash
git clone https://github.com/YadavPrince28/AI-POWERED-THREAT-DETECTION-AND-RESPONSE-SYSTEM
cd AI-POWERED-THREAT-DETECTION-AND-RESPONSE-SYSTEM
pip install -r requirements.txt
python app.py

Open in browser:
http://127.0.0.1:5000
```
---

## 📊 Key Modules
🔹 Detection Engine
  - Identifies attacks based on traffic patterns and behavior
  - Supports DDoS, Brute Force, and SQL Injection detection

🔹 Incident Management
- Automatically generates incidents
- Allows analyst assignment and investigation
- Supports status updates (Open → In Progress → Resolved)

🔹 Response System
  - Manual response via analyst actions
  - Automated mitigation (rate limiting, filtering)
  - Designed to handle distributed attacks efficiently

  🔹 Dashboard
  - Real-time visualization of threats
  - Displays severity, risk, and attack details

---

## 📌 Future Enhancements
- AI/ML-based anomaly detection
- Real-time alert notifications
- Attack visualization graphs
- Cloud deployment (AWS/Azure)
- Integration with SIEM tools

  ---

## 👥 Team Members
- Prince Kumar Yadav
- Saksham Luther
- Rohnit
- Manpreet Kaur
- Ishmeet Singh

---

## 👨‍💻 Author
**Prince Kumar Yadav**<br>
B.Tech CSE | Cybersecurity Enthusiast<br>
Focused on building intelligent security systems and real-world SOC solutions

---

## 📚 References
- MITRE ATT&CK Framework
- OWASP Top 10
- Flask Documentation
- Scapy Documentation
---
## 🧭 License
This project is developed for educational and research purposes only.
---
## ⭐ Support
If you found this project useful, consider giving it a ⭐ on GitHub.
