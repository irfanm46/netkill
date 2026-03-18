# NetKill — Immersive Cyber Range

> **Master cybersecurity through hands-on attack simulations and defensive challenges.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-irfanm46.github.io%2Fnetkill-00ff88?style=flat-square&logo=github)](https://irfanm46.github.io/netkill)
[![Version](https://img.shields.io/badge/Version-1.0.0-00d4ff?style=flat-square)](https://github.com/irfanm46/netkill/releases)
[![License](https://img.shields.io/badge/License-MIT-c084fc?style=flat-square)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-00ff88?style=flat-square)](https://github.com/irfanm46/netkill)

---

## What is NetKill?

NetKill is a **free, offline-first cyber range platform** built as a single HTML file. No servers, no signup, no backend — just open it in your browser and start practising.

It bridges the gap between reading about cybersecurity and actually doing it — mapping every attack scenario to real-world tools, MITRE ATT&CK techniques, and defensive countermeasures.

---

## Features

### 22 Attack Scenarios
Full kill chain simulations with real terminal commands, mapped to MITRE ATT&CK v14.

| Scenario | Tactics | Difficulty |
|---|---|---|
| NK-001: Phishing to Foothold | Initial Access, Execution | ★★☆☆☆ |
| NK-002: SQL Injection → Data Exfil | Initial Access, Exfiltration | ★★★☆☆ |
| NK-003: Pass-the-Hash Lateral Move | Credential Access, Lateral Movement | ★★★☆☆ |
| NK-004: Kerberoasting | Credential Access | ★★★☆☆ |
| NK-005: Ransomware Kill Chain | Impact | ★★★★★ |
| NK-006: Web Recon → RCE | Reconnaissance, Initial Access | ★★★★☆ |
| NK-007: Supply Chain Compromise | Initial Access | ★★★★★ |
| NK-008: Living off the Land (LOLBins) | Defense Evasion | ★★★☆☆ |
| NK-009: DNS Tunneling C2 | Command & Control | ★★★★☆ |
| NK-010: Process Injection | Defense Evasion | ★★★★☆ |
| NK-011: Sudo Privilege Escalation | Privilege Escalation | ★★☆☆☆ |
| NK-012: SSH Brute Force & Takeover | Credential Access | ★★☆☆☆ |
| NK-013: Cloud IAM Privilege Escalation | Privilege Escalation | ★★★★☆ |
| NK-014: Active Directory Enumeration | Discovery | ★★☆☆☆ |
| NK-015: BloodHound → Domain Admin | Lateral Movement | ★★★★★ |
| NK-016: Container Escape | Privilege Escalation | ★★★★☆ |
| NK-017: API Key Extraction & Abuse | Credential Access | ★★★☆☆ |
| NK-018: Insider Threat Data Theft | Exfiltration | ★★★☆☆ |
| NK-019: ARP Spoofing / MITM | Credential Access | ★★★☆☆ |
| NK-020: Password Spray Attack | Credential Access | ★★☆☆☆ |
| NK-021: Log Clearing & Anti-Forensics | Defense Evasion | ★★★☆☆ |
| NK-022: Zero-Day Exploit Chain | Initial Access | ★★★★★ |

### 8 Defensive Challenges
Real SOC analyst scenarios with authentic evidence — SIEM alerts, CloudTrail logs, network flows, PowerShell block logs. Multiple-choice with detailed analyst explanations.

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

### ◎ Skill Map
Track your MITRE ATT&CK coverage across all 13 tactics with real-time progress bars that update as you complete scenarios.

### Tools Reference
16 essential security tools (Nmap, Mimikatz, BloodHound, Burp Suite, Volatility, Impacket, and more) with descriptions and example commands.

### XP & Rank System
7 ranks from **Recruit** to **Elite Hacker**. Progress saved locally via `localStorage` — no account needed.

---

## Tech Stack

```
Single HTML file · Vanilla JS · Inline CSS · localStorage · GitHub Pages
82KB · Zero dependencies · Zero backend · Offline-first
```

---

## Getting Started

### Option 1 — Use the live version
Open **[irfanm46.github.io/netkill](https://irfanm46.github.io/netkill)** in your browser.

### Option 2 — Run locally
```bash
git clone https://github.com/irfanm46/netkill.git
cd netkill
# Open index.html directly in your browser — no build step needed
open index.html
```

---

## Roadmap

### v1.1 — Framework Mapper
- ISO 27001 ↔ NIST CSF ↔ SOC 2 ↔ MITRE ATT&CK cross-mapping
- Export coverage reports as PDF

### v1.2 — Scenario Builder
- Custom attack scenario creator
- Community scenario sharing (GitHub Gist integration)

### v2.0 — Interactive Lab
- Browser-based terminal emulator
- Guided step-by-step walkthroughs with hints
- Peer leaderboard and team challenges

---

## Related Projects

- **[Annexa](https://irfanm46.github.io/annexa)** — ISO 27001:2022 Engineer Toolkit (also open-source, zero dependencies)

---

## Contributing

Pull requests are welcome. Open an issue first to discuss what you'd like to change.

---

## Author

Built by **Irfan** — fresher targeting GRC Analyst / InfoSec Analyst roles. Learning by building.

[![GitHub](https://img.shields.io/badge/GitHub-irfanm46-181717?style=flat-square&logo=github)](https://github.com/irfanm46)

---

## License

NetKill is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](LICENSE.txt) license. You are free to use and share this project for non-commercial purposes, as long as you provide attribution and do not create derivatives.

---

*"The best way to understand attacks is to simulate them."*
