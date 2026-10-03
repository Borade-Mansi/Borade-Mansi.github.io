# Mansi Borade | Cyber Security Portfolio

Blue-team and SOC projects: detection, incident response, and machine learning for network security. Each project has its own folder with a README covering what I built, why, the tools I used and what I learned.

Live site: https://borade-mansi.github.io

## About me

- MSc Cyber Security, University of the West of Scotland (London), 2026
- BTech Computer Science (AI specialisation), Parul University
- Cybersecurity Intern at Syntecxhub (May 2026 to present)
- Earlier career as a software developer, web developer and UI/UX designer
- Based in London. Languages: English and Hindi
- Targeting roles: SOC Analyst, Security Analyst, Cyber Defence Analyst, Information Security Analyst

## Projects

| # | Project | What it shows | Tools | Status |
|---|---------|---------------|-------|--------|
| 1 | [Hybrid Intrusion Detection System](./1-hybrid-ids) | MSc dissertation: Random Forest + LSTM detection of malicious network traffic, evaluated on three datasets | Python, Scikit-learn, TensorFlow/Keras, FastAPI, Docker | Completed |
| 2 | [SOC Detection Lab](https://github.com/Borade-Mansi/SOC-Lab) | Kali attack against an Ubuntu SSH target, log evidence, Wazuh alert, investigation report | Kali Linux, Ubuntu, Wazuh | In progress |
| 3 | [Encrypted TCP Chat](./3-encrypted-chat) | Multi-threaded client/server chat with AES-256-CBC encryption | Python, sockets, cryptography | Completed |
| 4 | [Secure IoT Pipeline](./4-iot-mqtt-security) | MQTT pipeline secured with TLS and X.509 certificates, replay-attack tests, monitoring dashboard | Python, MQTT, TLS, Streamlit | Completed |
| 5 | [Incident Response Plan (S10 Media)](./5-incident-response-plan) | Full IR plan for a fictitious organisation | SANS, NIST CSF | Coursework |
| 7 | [Cryptanalysis and 7-bit PDU encoder](./7-applied-cryptography) | Broke a monoalphabetic substitution cipher in CrypTool 2 (dictionary and genetic analysis); Python 7-bit PDU encoder | Python, CrypTool 2 | Coursework |
| 6 | [NLP and LLM experiments](./6-nlp-experiments) | LoRA/PEFT fine-tuning, semantic search, BERT/RoBERTa classification | PyTorch, Hugging Face, spaCy | Completed |

### Coming next

| Project | Focus |
|---------|-------|
| Phishing Investigation | Email header and IOC extraction, Python enrichment and scoring, written report |
| IR Playbook | NIST-based playbook and tabletop exercise |
| Cloud and IAM Assessment | Over-permissioned roles and public buckets, with remediation write-up |
| Vulnerability Management Report | Nmap scan, risk-ranked findings, prioritised fix plan |
| Security Risk Assessment | Likelihood x impact rating and control recommendations on NIST CSF |
| Threat Intelligence Report | Finished OSINT report using the Diamond Model, kill chain, ATT&CK mapping, confidence levels and TLP |
| ARP Spoofing Detection | Detect ARP poisoning with Wireshark and Wazuh, with mitigations (dynamic ARP inspection, static entries, encryption) |
| Honeypot Lab | Low-interaction honeypot and honeytokens alerting into Wazuh |
| AI Security Lab | Local LLM (Ollama + Open WebUI) attacked with prompt injection, mapped to OWASP LLM Top 10, with defensive guardrails |

## Skills

| Area | Skills |
|------|--------|
| Detection and monitoring | Log analysis, alert triage, authentication log analysis, SIEM and IDS concepts, Wazuh, phishing analysis, MITRE ATT&CK mapping |
| Incident response and forensics | NIST 800-61, SANS, evidence collection from logs, incident reporting, zero-day and ransomware response scenarios |
| Threat intelligence, vulnerability and risk | Threat intelligence and triage assessment, vulnerability assessment, risk assessment, NIST CSF |
| Tools and platforms | Wazuh, Kali Linux, Ubuntu/Linux, CrypTool 2, Docker, Git, Streamlit, MQTT, TLS/X.509 |
| Scripting and automation | Python, JavaScript, PHP, FastAPI, MySQL |
| Machine learning | Scikit-learn, TensorFlow/Keras, PyTorch, Hugging Face Transformers, LoRA/PEFT, spaCy |
| AI security (learning) | OWASP Top 10 for LLM Applications (2025), prompt injection defences, MITRE ATLAS, guardrails |
| Offensive and identity knowledge | Network penetration testing concepts, red team operations management (CRTOM), IAM, applied cryptography |
| Documentation | Technical writing, written investigations, incident response plans |

Learning next: Splunk or ELK, Wireshark, Nmap, malware analysis fundamentals.

## AI security notes

Study notes on securing LLM applications, based on the OWASP Top 10 for LLM Applications (2025): prompt injection, sensitive information disclosure, supply chain, data and model poisoning, improper output handling, excessive agency, system prompt leakage, vector and embedding weaknesses, misinformation and unbounded consumption. Each has a defence. See the [live site](https://borade-mansi.github.io/#ai).

## Proof of work

- HackerDNA: ranked #277 globally, 12 labs, 3 root flags
- Every project documented in its own folder, with a written investigation for each lab

## Credentials

- ISC2 Certified in Cybersecurity course: Domain 1 Security Principles, and Domain 2 Incident Response, Business Continuity and Disaster Recovery Concepts (certificates issued January 2026)
- AIG Shields Up: Cybersecurity Job Simulation (Forage, June 2025): zero-day response, bypassing ransomware
- Tata Cybersecurity Analyst Job Simulation (Forage, June 2025): IAM fundamentals, strategy, custom IAM solutions, platform integration
- Deloitte Australia Cyber Job Simulation
- Certified Red Team Operations Management (CRTOM), Red Team Leaders, December 2025

## Repository layout

```
/1-hybrid-ids
/3-encrypted-chat
/4-iot-mqtt-security
/5-incident-response-plan
/6-nlp-experiments
/7-applied-cryptography
README.md
LICENSE
```

Each project folder follows the same template: **Overview, Tools, Method, Findings, What I learned**.

## Contact

- Email: borademansiv@gmail.com
- LinkedIn: https://www.linkedin.com/in/mansiborade
