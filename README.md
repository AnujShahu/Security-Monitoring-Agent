# 🛡️ Security Monitoring Agent

A lightweight **Security Monitoring Agent** built in Python to simulate **real-world SOC (Security Operations Center) log analysis**.
The system ingests structured logs, analyzes activity patterns, and generates alerts for suspicious behavior.



## 📌 Overview

Security teams rely on continuous log monitoring to detect threats such as brute-force attacks, compromised accounts, and malicious IP activity.
This project demonstrates how security logs can be processed and analyzed using rule-based detection techniques in a modular and extensible design.

## ✨ Features

* Log ingestion from CSV files
* Log normalization for consistent processing
* Brute-force login detection
* Threat intelligence matching (known malicious IPs)
* Critical account monitoring (admin/root)
* High-activity anomaly detection
* Configurable detection thresholds
* Clear alert generation and logging


## 🏗️ Architecture


Log Data → Normalization → Detection Engine → Alerts


Detection Engine Modules:

* Brute-force Detection
* Threat Intelligence Matching
* Critical Account Monitoring
* Activity Volume Anomaly Detection



## 🧰 Tech Stack

* **Language:** Python 3.10+
* **Library:** pandas
* **Logging:** Python logging module
* **Data Format:** CSV

---
## 🚀 How to Run

```bash
pip install -r requirements.txt
python src/security_monitoring_agent.py
```

---

## 🧪 Sample Output

```
BRUTE FORCE ALERT: 192.168.1.100 targeting user admin
THREAT INTEL ALERT: Known malicious IP detected -> 10.0.0.99
CRITICAL ACCOUNT ALERT: Failed activity on root from 203.0.113.45
ANOMALY ALERT: High event volume from IP 10.0.0.99
```

---

## 🎯 Use Cases

* SOC analyst practice
* Cybersecurity portfolio project
* Interview and academic demonstrations
* Foundation for advanced security monitoring systems



## 📂 Dataset

The dataset simulates authentication, file access, and API activity, including both normal and malicious behavior, designed to resemble enterprise security logs.
