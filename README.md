# 🕵️ Cyber Threat Intelligence (CTI) System

## 📌 Overview
A Python-based CTI framework that collects, analyzes, and interprets 
cyber threat indicators from multiple intelligence sources to support 
threat hunting and SOC investigation workflows.

## 🛠️ Tools & Technologies
- Python (CLI-based)
- VirusTotal API
- AbuseIPDB
- AlienVault OTX
- Shodan
- MITRE ATT&CK Framework
- MISP (Malware Information Sharing Platform)

## 🎯 Key Features
- IOC analysis: IP addresses, Domains, URLs, File Hashes
- Threat scoring and reputation checking
- Multi-source intelligence collection (OSINT + APIs)
- Structured CLI output with threat context
- Foundation for MITRE ATT&CK mapping & SIEM integration

## 🚀 How It Works
1. User inputs an IOC (IP / Domain / URL / Hash) via CLI
2. System queries VirusTotal, AbuseIPDB, OTX APIs
3. Threat score and reputation are calculated
4. Final report displayed with threat context

## 📄 Project Report
See full report: [Cyber_Threat_Intelligence.docx]

## 🔮 Future Work
- MITRE ATT&CK matrix visualization
- GUI-based dashboard
- Real-time alerting
- SIEM integration (Splunk / Wazuh)
- AI-based threat prediction

## 📚 References
VirusTotal, AbuseIPDB, Shodan, MITRE ATT&CK, AlienVault OTX
