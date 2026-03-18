# NetKill — Immersive Cyber Range

> **Master cybersecurity through hands-on attack simulations and defensive challenges.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-irfanm46.github.io%2Fnetkill-00ff88?style=flat-square&logo=github)](https://irfanm46.github.io/netkill)
[![Version](https://img.shields.io/badge/Version-3.0.0-00d4ff?style=flat-square)](https://github.com/irfanm46/netkill/releases)
[![License](https://img.shields.io/badge/License-Custom-c084fc?style=flat-square)](LICENSE.txt)

---

## What is NetKill?

NetKill is a **closed-source, browser-based cyber range platform** that provides hands-on, gamified experiences for mastering offensive and defensive cybersecurity skills. It offers a realistic, simulated environment where users can explore various cybersecurity concepts, techniques, and tools through interactive scenarios and challenges.

---

## Terms of Use

By using NetKill, you agree to be bound by the terms and conditions outlined in the [NetKill License Agreement](LICENSE.txt). Key points to note:

- NetKill is a closed-source project. The source code is not available for public access, modification, or distribution.
- You may use NetKill through the provided GitHub Pages link for personal, non-commercial purposes only.
- You may not modify, adapt, or create derivative works based on NetKill.
- You may not use NetKill for any commercial purposes without express written permission from the project owner.
- You may not distribute, sublicense, or transfer NetKill to any third party.

Please read the full [NetKill License Agreement](LICENSE.txt) before using the project.

---

## Features

### 27 Offensive Scenarios
Full kill chain simulations with real terminal commands, mapped to MITRE ATT&CK v14.

| Scenario | Tactics | Difficulty |
|---|---|---|
| NK-001 - NK-022 | (same as before) | (same as before) |
| NK-023: SSRF → AWS Cloud Metadata | Initial Access, Credential Access | ★★★☆☆ |
| NK-024: OAuth 2.0 App Abuse | Initial Access, Collection | ★★★★☆ |
| NK-025: Kubernetes Pod Escape | Privilege Escalation | ★★★★★ |
| NK-026: CI/CD Pipeline Injection | Initial Access, Exfiltration | ★★★★☆ |
| NK-027: LDAP Injection → AD Dump | Initial Access, Discovery | ★★★☆☆ |

### 13 Defensive Challenges
Real SOC analyst scenarios with authentic evidence — SIEM alerts, logs, network flows, and more.

| Challenge | Type | XP |
|---|---|---|
| DC-001: Kerberoasting Alert Triage | SIEM Analysis | 150 XP |
| DC-002: Suspicious PowerShell Investigation | Forensics | 200 XP |
| DC-003: C2 Traffic Identification | Network Analysis | 175 XP |
| DC-004: Ransomware Incident Response | IR | 250 XP |
| DC-005: Sigma Detection Rule Challenge | Detection Engineering | 300 XP |
| DC-006: Firewall Log Analysis — Exfiltration | Network Analysis | 175 XP |
| DC-007: Cloud Breach Investigation | Cloud Forensics | 225 XP |
| DC-008: Insider Threat UEBA Review | UEBA | 200 XP |
| DC-009: Kubernetes API Anomaly | Detection | 250 XP |
| DC-010: OAuth Consent Phishing | Analysis | 200 XP |
| DC-011: WMI Lateral Movement | Hunting | 300 XP |
| DC-012: CI/CD Secret Exposure | Triage | 225 XP |
| DC-013: Password Spray vs Brute Force | Detection | 175 XP |

### 7 Incident Response Playbooks
Interactive guides for real-world incident handling — from identification to lessons learned.

| Playbook | Scenario | Steps |
|---|---|---|
| IR-001: Ransomware Outbreak | Enterprise-wide ransomware infection | 12 |
| IR-002: AWS EC2 Cryptojacking | Unauthorized Bitcoin mining | 9 |
| IR-003: Business Email Compromise | CEO fraud, wire transfer scam | 10 |
| IR-004: Insider Data Theft | Departing employee exfiltration | 11 |
| IR-005: Supply Chain Backdoor | Compromised CI/CD pipeline | 13 |
| IR-006: Office 365 Phishing | Credential harvesting, mailbox compromise | 10 |
| IR-007: Accidental Disclosure | Sensitive data exposure, regulatory risk | 8 |

### Threat Hunt Lab
5 hands-on hunting exercises using real query languages (KQL, SPL).

- Structured methodology: Hypothesis → Data Sources → Query → IOCs → ATT&CK
- Checkable steps with XP rewards, tracked in localStorage

### 20 Security Tools
Essentials for offensive, defensive, and IR teams — with descriptions and example commands.

### Dashboard & Progress Tracking 
Live stats on completed scenarios, challenges, XP, and Hunt coverage. Export/import to save your progress.

---

## Getting Started

Open **[irfanm46.github.io/netkill](https://irfanm46.github.io/netkill)** in your browser to access NetKill. The project is not available for local installation or modification.

---

## Contact

If you have any questions, feedback, or inquiries regarding commercial use or licensing, please contact the project owner at [irfan@example.com].

---

## Related Projects

- **[Annexa](https://irfanm46.github.io/annexa)** — ISO 27001:2022 Engineer Toolkit

---

## License

NetKill is licensed under a [custom license agreement](LICENSE.txt). You are free to use NetKill through the provided GitHub Pages link for personal, non-commercial purposes only, subject to the terms and conditions outlined in the license agreement. Any unauthorized use, reproduction, or distribution of NetKill is strictly prohibited.

---

*"To beat a hacker, you need to think like one."*
