# Security Analytics & Threat Hunting

<p align="center">
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/MITRE%20ATT%26CK-E22C2C?style=for-the-badge&logo=target&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkMiner-0078D4?style=for-the-badge&logo=windows&logoColor=white" />
</p>

> Graduate-level cybersecurity analytics portfolio covering network traffic analysis, threat hunting, digital forensics, incident response, system log analysis, and **machine learning-based intrusion detection** — combining hands-on security tooling with data science for advanced threat detection.

---

## Overview

This repository documents hands-on security analytics work completed during **graduate-level Cybersecurity Analytics coursework** at Minnesota State University Moorhead. It bridges traditional network security analysis with modern **machine learning approaches** to intrusion detection — making it directly relevant to both industry SOC roles and academic research.

**Highlights:**
- KNN-based ML model for network intrusion detection using the KDD dataset
- Full incident response case study for a simulated banking breach
- Ransomware threat intelligence analysis (Medusa ransomware / SimonMed Imaging)
- 9 progressive labs from basic packet analysis to ML model deployment

---

## Contents at a Glance

| # | Type | Title | Key Tools |
|---|------|-------|-----------|
| Lab 1 | Lab | Packet Analysis with Wireshark | Wireshark |
| Lab 2 | Lab | Live Traffic Capture & Analysis | Wireshark, tcpdump |
| Lab 3 | Lab | Network Investigation via Packet Analysis | Wireshark |
| Lab 4 | Lab | Network Forensics using NetworkMiner | NetworkMiner |
| Lab 5 | Lab | Cybersecurity Incident Investigation | Wireshark, ProcMon |
| Lab 6 | Lab | Traffic Analysis using tcpdump | tcpdump |
| Lab 7 | Lab | System Logging & Syslog Analysis | Syslog, rsyslog |
| Lab 8 | Lab | Machine Learning Environment Setup | Python, Scikit-Learn |
| Lab 9 | Lab | ML Model for Cyber Attack Detection | KNN, Python |
| Project 1 | Project | Xfibility Bank Incident Response | Wireshark, MITRE ATT&CK |
| Project 2 | Project | KNN Intrusion Detection System | Python, Scikit-Learn, KDD |
| Project 3 | Project | Medusa Ransomware Threat Analysis | MITRE ATT&CK, CTI |

---

## Labs

### Lab 1 — Packet Analysis with Wireshark
Introduction to packet capture and protocol analysis using Wireshark filters, stream following, and traffic dissection.

### Lab 2 — Live Traffic Capture & Analysis
Real-time network traffic capture and live protocol analysis identifying normal vs. suspicious traffic patterns.

### Lab 3 — Network Investigation via Packet Analysis
Forensic-style investigation of a PCAP file to identify suspicious hosts, unusual connections, and potential indicators of compromise.

### Lab 4 — Network Forensics using NetworkMiner
Passive network forensics using NetworkMiner to extract hosts, sessions, files, credentials, and artifacts from packet captures without active probing.

### Lab 5 — Cybersecurity Incident Investigation
End-to-end incident investigation combining network packet analysis with host-based process monitoring (ProcMon/Autoruns) to reconstruct an attack timeline.

### Lab 6 — Traffic Analysis using tcpdump
Command-line packet capture and filtering using tcpdump — capturing specific protocols, filtering by host/port, and writing PCAPs for offline analysis.

### Lab 7 — System Logging & Syslog Analysis
Configuring centralized logging using Syslog/rsyslog, analyzing log events for anomalies, and correlating log data with network traffic.

### Lab 8 — Machine Learning Environment Setup
Setting up a Python ML environment (Pandas, Matplotlib, Scikit-Learn) and preparing the KDD Cup dataset for cybersecurity classification tasks.

### Lab 9 — Machine Learning Model for Cyber Attack Detection
Training and evaluating a **K-Nearest Neighbor (KNN)** classifier on the KDD Cup dataset to detect network intrusions — including feature selection, model training, accuracy evaluation, and confusion matrix analysis.

---

## Projects

---

### Project 1 — Xfibility Bank Incident Response & Mitigation Plan

**Scenario:** Xfibility Bank has suffered a suspected data breach. Conduct a full incident investigation and produce an executive-level mitigation plan.

| Phase | Activity |
|-------|---------|
| Investigation | Network traffic analysis and log correlation |
| Attribution | Attack vector identification |
| Mapping | MITRE ATT&CK technique mapping |
| Reporting | Incident timeline, findings, and remediation |
| Mitigation | Security controls and NIST framework recommendations |

**Key Deliverable:** Executive presentation + technical incident report with risk-prioritized recommendations.

**Skills:** Incident Response · Network Forensics · MITRE ATT&CK · Risk Assessment · Security Controls · Executive Reporting

---

### Project 2 — KNN Classifier for Network Intrusion Detection

**Objective:** Build and evaluate a Machine Learning model to classify network traffic as normal or attack using the KDD Cup 1999 dataset.

#### Approach

```
Dataset      →  KDD Cup 1999 (network intrusion detection benchmark)
Preprocessing →  Feature selection, normalization, train/test split
Model        →  K-Nearest Neighbor (KNN) Classifier
Evaluation   →  Accuracy, Precision, Recall, Confusion Matrix
Output       →  Trained classifier with performance analysis
```

#### Results

| Metric | Value |
|--------|-------|
| Algorithm | K-Nearest Neighbor (KNN) |
| Dataset | KDD Cup 1999 |
| Task | Multi-class attack classification |
| Evaluation | Accuracy, Confusion Matrix, Classification Report |

**Attack Categories Detected:** DoS · Probe · R2L · U2R

**Skills:** Python · Scikit-Learn · Pandas · Matplotlib · KNN · Feature Engineering · Intrusion Detection · ML Model Evaluation

---

### Project 3 — Medusa Ransomware Threat Intelligence Analysis

**Case:** Analysis of the **Medusa ransomware** attack on **SimonMed Imaging** — a real-world healthcare sector breach.

| Analysis Area | Details |
|--------------|---------|
| Threat Actor | Medusa ransomware group |
| Target | SimonMed Imaging (healthcare) |
| Framework | MITRE ATT&CK full TTP mapping |
| Intelligence | Cyber Kill Chain stage mapping |
| Impact | Patient data exposure, operational disruption |
| Defense | Detection strategies and security control recommendations |

#### MITRE ATT&CK Coverage

| Tactic | Techniques Analyzed |
|--------|-------------------|
| Initial Access | Phishing, Exploit Public-Facing Application |
| Execution | PowerShell, WMI |
| Persistence | Registry Run Keys, Scheduled Tasks |
| Defense Evasion | Obfuscation, Disable Security Tools |
| Exfiltration | Exfiltration over C2 Channel |
| Impact | Data Encrypted for Impact (T1486) |

**Skills:** Threat Intelligence · MITRE ATT&CK · Ransomware Analysis · Healthcare Security · Cyber Kill Chain · CTI Reporting

---

## Repository Contents

```
Security-analytics-and-threat-hunting
├── 📄 README.md
├── 📋 Cybersecurity Analytics - Lab 1 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Lab 2 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Lab 3 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Lab 4 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Lab 5 -Project 1- Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Lab 6 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Lab 7 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Lab 8 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Lab 9 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Project 2 - Hashan Kodippilige.pdf
├── 📋 Cybersecurity Analytics - Project 3 - Hashan Kodippilige.pdf
├── 📊 KNN-Presentation.pptx-Hashan_Kodippilige.pdf
├── 📊 Medusa-Presentation.pptx-Hashan_Kodippilige.pdf
└── 📊 Xfibility Bank.pptx-Hashan_Kodippilige.pdf
```

---

## Tools & Technologies

| Category | Tools |
|----------|-------|
| Network Analysis | Wireshark, NetworkMiner, tcpdump |
| System Monitoring | Process Monitor (ProcMon), Autoruns, Syslog, rsyslog |
| Machine Learning | Python, Scikit-Learn, Pandas, Matplotlib |
| ML Algorithms | K-Nearest Neighbor (KNN), Decision Tree |
| Frameworks | MITRE ATT&CK, Cyber Kill Chain, NIST |
| Dataset | KDD Cup 1999 (Network Intrusion Detection) |

---

## Skills Demonstrated

`Network Traffic Analysis` `Wireshark` `NetworkMiner` `tcpdump` `Syslog` `Threat Hunting` `Incident Response` `Machine Learning` `KNN Classifier` `Intrusion Detection` `Python` `Scikit-Learn` `MITRE ATT&CK` `Ransomware Analysis` `Threat Intelligence` `Healthcare Security` `Security Analytics` `Cyber Kill Chain`

---

## Real-World Relevance

This portfolio is directly applicable to:
- **SOC Analyst** roles — threat hunting, traffic analysis, log correlation, incident response
- **Threat Intelligence Analyst** roles — ransomware TTP mapping, CTI reporting
- **Security Data Scientist** roles — ML-based intrusion detection, anomaly detection
- **PhD Research** — ML/AI applications in cybersecurity, ransomware behavior analysis, healthcare sector security

---

## Disclaimer

All investigations were conducted in authorized educational lab environments. The Medusa/SimonMed analysis is based on publicly available threat intelligence for academic research purposes only.

---

## Author

**Hashan Kodippilige**  
M.S. Cybersecurity — Minnesota State University Moorhead  
📧 hashansharindu@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hashankodippilige/)  
🐙 [GitHub](https://github.com/hashan-kodippilige)
