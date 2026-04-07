# 🔐 AI-Driven Secure Code Auditor for Detecting OWASP Vulnerabilities

## 📌 Overview
The AI-Driven Secure Code Auditor is an intelligent security tool designed to automatically detect vulnerabilities in web applications based on OWASP Top 10 guidelines. With the increasing use of web applications in business, banking, healthcare, and communication, security risks such as SQL Injection, Cross-Site Scripting (XSS), and broken authentication have become major concerns.

This project combines static code analysis and machine learning techniques to identify insecure coding patterns and potential vulnerabilities in source code. The system analyzes input files, detects vulnerabilities, assigns severity levels, and generates a structured security report with recommended fixes.

By automating vulnerability detection, this tool helps developers build secure and reliable web applications while reducing manual effort, time, and security risks.

---

## 🎯 Objectives
- Detect OWASP Top 10 vulnerabilities automatically  
- Reduce manual code review effort  
- Improve vulnerability detection accuracy  
- Generate structured security reports  
- Provide suggestions for fixing security issues  

---

## ⚙️ Features
- Static Code Analysis  
- AI-Based Vulnerability Detection  
- OWASP Top 10 Vulnerability Detection  
- Severity Classification (Low, Medium, High)  
- Structured Security Report  
- Command Line Interface (CLI)  
- GUI Support (Optional)  

---

## 🛡️ OWASP Vulnerabilities Covered
- SQL Injection  
- Cross-Site Scripting (XSS)  
- Broken Authentication  
- Sensitive Data Exposure  
- Security Misconfiguration  
- Broken Access Control  
- Insecure Deserialization  
- Using Components with Known Vulnerabilities  
- Insufficient Logging & Monitoring  
- Cross-Site Request Forgery (CSRF)  

---

## 🧰 Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-learn  
- TensorFlow / PyTorch  

### Static Analysis Tools
- Semgrep  
- Bandit  
- Custom Rule Engine  

### Framework (Optional GUI)
- Flask / Django  

### Other Tools
- Git & GitHub  
- Pandas & NumPy  
- Docker (Optional)  

---

## 📁 Project Structure
AI-Secure-Code-Auditor/
│
├── dataset/
├── models/
├── scanner/
├── reports/
├── utils/
├── app.py
├── requirements.txt
└── README.md
