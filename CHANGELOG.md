# Changelog

All notable changes to the NetKill project will be documented in this file.

## [3.0.0] - 2026-03-19

### Added
- 5 new offensive scenarios:
  - NK-023: SSRF → AWS Cloud Metadata (IMDSv2, IAM credential theft)
  - NK-024: OAuth 2.0 App Abuse (illicit consent grant, M365 email collection)
  - NK-025: Kubernetes Pod Escape (privileged pod → host root)
  - NK-026: CI/CD Pipeline Injection (GitHub Actions secret exfil)
  - NK-027: LDAP Injection → AD Dump (web app to domain enumeration)

- 5 new SOC challenges:
  - DC-009: Kubernetes API Anomaly (cluster takeover detection)
  - DC-010: OAuth Consent Phishing (Entra ID log analysis)
  - DC-011: WMI Lateral Movement (Sysmon + Event 4648)
  - DC-012: CI/CD Secret Exposure (immediate priority decision)
  - DC-013: Password Spray vs Brute Force (detection & triage)

- 2 new IR playbooks:
  - IR-006: Supply Chain Compromise (npm/CI backdoor response)
  - IR-007: Business Email Compromise (BEC/CEO fraud playbook)

- Brand new Threat Hunt Lab with 5 exercises:
  - Real KQL (Microsoft Sentinel) + SPL (Splunk) hunt queries
  - Structured methodology: Hypothesis → Data Sources → Query → IOCs → ATT&CK
  - Checkable steps with XP rewards, tracked in localStorage

- 4 new tools: YARA, Zeek, Falco, Trivy (20 tools total)

- Progress Export/Import — back up and restore your save as JSON

- Dashboard — now shows all 5 stats including Hunt completion, with live counts reflecting the expanded content.

### Changed
- Updated offensive scenario descriptions with higher-quality, story-driven intros
- Improved SOC challenge navigation and answer validation
- Threat Hunt Lab replaces the previous Hunt Hints section
- Reorganized Tools page with categories and new additions
- Polished UI with cleaner layout, smoother transitions, and refined graphics

### Fixed
- Resolved scoring issue where final scenario XP was not being awarded
- Fixed a bug in the SOC challenges where file attachments were not loading
- Addressed minor typos and grammatical errors in scenario and challenge text

## [2.0.0] - 2026-02-15
- ...

## [1.0.0] - 2026-01-04
- ...
