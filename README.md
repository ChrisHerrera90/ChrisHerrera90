# <a href="https://www.linkedin.com/in/chris-herrera-grc/">Christopher Herrera</a>'s GRC and Cybersecurity Project Portfolio 🔐
### GRC Engineer | FedRAMP CR26 & FISMA RMF | Compliance as Code (AWS, Terraform, Python)

I build compliance evidence the way engineers build software: as code that runs, gets tested in CI, and produces the artifacts an assessor or authorizing official actually needs t pass reviews.
My current lab work follows FedRAMP's Consolidated Rules for 2026 (CR26) and the NIST Risk Management Framework used for FISMA authorizations. It's built on one AWS system defined in Terraform, with vulnerability reporting, a machine-readable certification package, change notification, and a full agency ATO package, all mapped to NIST SP 800-53 Rev. 5.

**Tools:** AWS · Terraform · Python · GitHub Actions · JSON / OSCAL · Splunk · KQL 
**Open to:** GRC Engineering, GRC Analyst, and junior ISSO roles on FedRAMP and federal teams.

---

# ⚙️ GRC Engineering Projects
## 🏛️ FedRAMP & FISMA Compliance-as-Code Labs
*Self-built labs on a single AWS system. Status and links updated as each one ships.*

| Project | What it produces | Status | Target |
|---|---|---|---|
| **FedLab: FedRAMP-Scoped AWS Reference System (Terraform)** | Terraform-built app, Minimum Assessment Scope boundary, automated asset inventory | In progress | Dec 2026 |
| **FedRAMP CR26 Vulnerability Detection & Response (VDR/VER) Pipeline** | Scanner + custom Python checks → findings graded by reachability, exploitability and impact → monthly machine-readable report + legacy POA&M export | Planned | Jan 2027 |
| **FedRAMP Certification Package as Code (CPO + SDR)** | ~25 controls documented in JSON, validated in CI, with OSCAL SSP export | Planned | Feb 2027 |
| **FedRAMP Significant Change Notification (SCN) Pipeline** | GitHub Action that classifies Terraform changes as routine, adaptive or transformative and writes the notification | Planned | Feb 2027 |
| **Municipal Cybersecurity Assessment: NIST CSF 2.0 + FISMA IG Maturity Model** | Current-state assessment, maturity scoring, prioritized remediation roadmap | Planned | Feb 2027 |
| **FISMA Agency ATO Package: Full NIST RMF Lifecycle** | All 7 RMF steps, SAP/SAR for 20 controls, ATO memo, continuous monitoring (ISCM) strategy, FY26 CIO metric crosswalk | Planned | Mar 2027 |

---

## ☁️ Cloud Security & Continuous Monitoring Labs

| Project | What it shows | NIST 800-53 | Tools |
|---|---|---|---|
| **[AWS Security Logging & Continuous Monitoring Lab](https://github.com/ChrisHerrera90/Complete-AWS-Cloud-Security-Architecture-Design-and-Splunk-Detection-Against-Simlulated-Attacks)** | AWS log pipeline into Splunk with detections tested against simulated attacks | AU-2, AU-6, AU-12, SI-4 | AWS, CloudTrail, Splunk |

---

## 🛡️ Vulnerability Management & Configuration Hardening Labs

| Project | What it shows | NIST 800-53 | Tools |
|---|---|---|---|
| **[Vulnerability Management Program Implementation](https://github.com/ChrisHerrera90/vulnerability-management-program)** | End-to-end program: policy, scanning, risk-based prioritization, remediation tracking | RA-5, SI-2, CA-7 | [scanner], PowerShell |
| **[DISA STIG Remediation as Code (PowerShell & Bash)](https://github.com/ChrisHerrera90/Powershell-and-Bash-Remediation-Scripts)** | Scripted fixes for federal STIG findings on Windows and Linux, verified by rescan | CM-6, CM-2, SI-2 | PowerShell, Bash |
| **[CIS Critical Security Controls Implementation](https://github.com/ChrisHerrera90/CIS-controls-project)** | Control assessment and implementation plan, crosswalked to NIST 800-53 | CIS v8 → 800-53 crosswalk | [tools] |

---

## 🚨 Security Operations Labs: Detection, Threat Hunting & Incident Response

| Project | What it shows | NIST 800-53 | Tools |
|---|---|---|---|
| **[Detection Engineering: T1059 Command & Scripting Interpreter](https://github.com/ChrisHerrera90/T1059---Command-and-Scripting-Interpreter-Incident-Response-Atomic-Red)** | Simulated attack, custom detection, full incident response write-up | SI-4, IR-4, AU-6 | Atomic Red Team, Azure, KQL |
| **[KQL Detection Rule Library](https://github.com/ChrisHerrera90/KQL-Detection-Rule-Library)** | Reusable detection rules for common cloud and endpoint threats | SI-4, AU-6 | KQL |
| **[Threat Hunt: Brute Force Attack](https://github.com/ChrisHerrera90/Threathunt-Bruteforce)** | Hypothesis-driven hunt, findings, and lockout recommendations | AC-7, SI-4, IR-4 | KQL |
| **[Threat Hunt: Unauthorized TOR Browser](https://github.com/ChrisHerrera90/Threat-Hunting-TOR-browser)** | Detecting unapproved software and anonymization tools | CM-7, CM-11, SI-4 | KQL |
| **[Threat Hunt: Crypto Mining Attack](https://github.com/ChrisHerrera90/ThreatHunt-Cryptominer)** | Detecting and scoping malicious resource abuse | SI-3, SI-4, IR-4 | KQL |
| **[Phishing Analysis: Credential Harvester](https://github.com/ChrisHerrera90/phishing-analysis-report1)** | Full email investigation with written incident report | IR-4, SI-8 | [tools] |
  
<hr/>

## 🤳 Connect With Me

[<img align="left" alt="___________ | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube]
[<img align="left" alt="___________ | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="chris-herrera-cyber | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="___________ | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

[twitter]: https://twitter.com/___________
[youtube]: https://www.youtube.com/c/___________
[instagram]: https://www.instagram.com/___________
[linkedin]: https://linkedin.com/in/chris-herrera-90

<!--
<img width="35" alt="image" src="https://github.com/user-attachments/assets/2f41c7cd-5ea8-4475-b451-a37161b6c3fb"> 
<img width="35" alt="image" src="https://github.com/user-attachments/assets/77649969-9910-4994-8b96-74a116cfb2a8">
-->
