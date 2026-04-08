<div align="center">

```
 ██████╗██████╗ ███████╗ ██████╗████████╗███████╗██████╗
██╔════╝██╔══██╗██╔════╝██╔════╝╚══██╔══╝██╔════╝██╔══██╗
╚█████╗ ██████╔╝█████╗  ██║        ██║   █████╗  ██████╔╝
 ╚═══██╗██╔═══╝ ██╔══╝  ██║        ██║   ██╔══╝  ██╔══██╗
██████╔╝██║     ███████╗╚██████╗   ██║   ███████╗██║  ██║
╚═════╝ ╚═╝     ╚══════╝ ╚═════╝   ╚═╝   ╚══════╝╚═╝  ╚═╝

██████╗ ██████╗ ███████╗ █████╗  ██████╗██╗  ██╗
██╔══██╗██╔══██╗██╔════╝██╔══██╗██╔════╝██║  ██║
██████╔╝██████╔╝█████╗  ███████║██║     ███████║
██╔══██╗██╔══██╗██╔══╝  ██╔══██║██║     ██╔══██║
██████╔╝██║  ██║███████╗██║  ██║╚██████╗██║  ██║
╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
```

### `"Offensive Intelligence. Defensive Automation."`

Open-source security tools for cloud security professionals · Built by practitioners · Used in the field

[![Repos](https://img.shields.io/badge/Repos-38-4D148C?style=for-the-badge&logoColor=white)](https://github.com/orgs/SpecterBreach/repositories)
[![AI Agents](https://img.shields.io/badge/AI_Security_Agents-8-FF6600?style=for-the-badge&logoColor=white)](https://github.com/SpecterBreach/CyberOpsOrchestrator)
[![Clouds](https://img.shields.io/badge/Clouds-OCI_·_AWS_·_Azure_·_GCP-00D4FF?style=for-the-badge&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-00C875?style=for-the-badge&logoColor=white)](#)

</div>

---

## `> cat mission.txt`

```
SpecterBreach builds open-source security tools for cloud security professionals.

We combine three things nobody else does together:
  [1] OCI-native cloud security tooling  — the only deep OCI security suite in OSS
  [2] Autonomous AI security agents      — Claude-powered agents that think, hunt, fix
  [3] Real-time threat intel engine      — CVEs auto-published to 6 platforms, 24/7

Everything here is built by practitioners, tested in real multi-cloud environments,
and released free for the global security community.
```

---

## `> ls repos/ --by-category`

### ☁️ Cloud Security Tools

| Repo | Description | Stars |
|---|---|---|
| [🐐 CloudGoat-OCI](https://github.com/SpecterBreach/CloudGoat-OCI) | **FLAGSHIP** — Vulnerable-by-design OCI environment. 8 CTF scenarios: IAM privesc, IDCS takeover, IMDS theft, VCN escape, Cloud Guard bypass, PAR abuse. First OCI equivalent of Rhino Security's CloudGoat. | ![](https://img.shields.io/github/stars/SpecterBreach/CloudGoat-OCI?style=flat-square&color=4D148C) |
| [🛡️ CloudSentinel](https://github.com/SpecterBreach/CloudSentinel) | Multi-cloud IAM auditor for OCI · AWS · Azure · GCP. Detects non-federated users, MFA gaps, overpermissioned policies, stale credentials. AI remediation scripts included. | ![](https://img.shields.io/github/stars/SpecterBreach/CloudSentinel?style=flat-square&color=4D148C) |
| [🔍 CSPMlite](https://github.com/SpecterBreach/CSPMlite) | Lightweight open-source CSPM dashboard. CIS benchmark auto-checker with React UI and persistent finding history. | ![](https://img.shields.io/github/stars/SpecterBreach/CSPMlite?style=flat-square&color=4D148C) |
| [🏷️ TagHunter](https://github.com/SpecterBreach/TagHunter) | Cross-cloud resource tag compliance scanner. Identifies untagged, mis-tagged resources. Supports EAI tag frameworks. | ![](https://img.shields.io/github/stars/SpecterBreach/TagHunter?style=flat-square&color=4D148C) |
| [🔐 MFAWatch](https://github.com/SpecterBreach/MFAWatch) | Identity audit tool flagging MFA gaps across cloud IAM users. OCI Classic IAM + IDCS, AWS, Azure. AI-generated remediation emails. | ![](https://img.shields.io/github/stars/SpecterBreach/MFAWatch?style=flat-square&color=4D148C) |
| [📊 PolicyScorer](https://github.com/SpecterBreach/PolicyScorer) | IAM policy risk scoring engine. Wildcard detector, cross-account trust graph, AI explanation of risky statements. | ![](https://img.shields.io/github/stars/SpecterBreach/PolicyScorer?style=flat-square&color=4D148C) |
| [🕸️ OCIAttackGraph](https://github.com/SpecterBreach/OCIAttackGraph) | OCI privilege escalation path mapper using Neo4j. Finds shortest path to admin across all IAM policies in a tenancy. | ![](https://img.shields.io/github/stars/SpecterBreach/OCIAttackGraph?style=flat-square&color=4D148C) |
| [🔄 CloudDriftDetector](https://github.com/SpecterBreach/CloudDriftDetector) | Detects config drift between Terraform IaC and live cloud state. Alerts on unauthorized manual changes. OCI · AWS · Azure. | ![](https://img.shields.io/github/stars/SpecterBreach/CloudDriftDetector?style=flat-square&color=4D148C) |
| [🔑 SecretScannerAI](https://github.com/SpecterBreach/SecretScannerAI) | AI-powered cloud storage secret scanner. Finds hardcoded keys, tokens, passwords in OCI Object Storage, S3, Azure Blob. LLM validation cuts false positives. | ![](https://img.shields.io/github/stars/SpecterBreach/SecretScannerAI?style=flat-square&color=4D148C) |

---

### 🤖 AI Security Agents

| Agent | Mission | Stars |
|---|---|---|
| [⚡ CyberOpsOrchestrator](https://github.com/SpecterBreach/CyberOpsOrchestrator) | **Master coordinator** — routes security tasks to specialist agents, manages parallel execution, aggregates findings. | ![](https://img.shields.io/github/stars/SpecterBreach/CyberOpsOrchestrator?style=flat-square&color=FF6600) |
| [🛡️ CloudGuardianAI](https://github.com/SpecterBreach/CloudGuardianAI) | 24/7 autonomous cloud posture monitor. Detects misconfigs → Terraform fixes → Slack/Teams alerts → Jira tickets. | ![](https://img.shields.io/github/stars/SpecterBreach/CloudGuardianAI?style=flat-square&color=FF6600) |
| [🔍 ThreatHunterAI](https://github.com/SpecterBreach/ThreatHunterAI) | AI-driven SIEM threat hunting. 100% MITRE ATT&CK mapped. ELK · Splunk · Sentinel. | ![](https://img.shields.io/github/stars/SpecterBreach/ThreatHunterAI?style=flat-square&color=FF6600) |
| [🔴 PenTestAgentAI](https://github.com/SpecterBreach/PenTestAgentAI) | Autonomous red team agent with scope enforcement and human approval gates. | ![](https://img.shields.io/github/stars/SpecterBreach/PenTestAgentAI?style=flat-square&color=FF6600) |
| [🕸️ IAMAnalyzerAI](https://github.com/SpecterBreach/IAMAnalyzerAI) | IAM privilege escalation path agent. Neo4j graph across OCI · AWS · Azure. | ![](https://img.shields.io/github/stars/SpecterBreach/IAMAnalyzerAI?style=flat-square&color=FF6600) |
| [🚨 SOCAnalystAI](https://github.com/SpecterBreach/SOCAnalystAI) | AI L1 SOC analyst. Triages → enriches → creates Jira/ServiceNow tickets automatically. | ![](https://img.shields.io/github/stars/SpecterBreach/SOCAnalystAI?style=flat-square&color=FF6600) |
| [📰 CVEResearcherAI](https://github.com/SpecterBreach/CVEResearcherAI) | 24/7 CVE monitoring + AI enrichment + auto-publishing to LinkedIn · Reddit · X · Discord · Telegram. | ![](https://img.shields.io/github/stars/SpecterBreach/CVEResearcherAI?style=flat-square&color=FF6600) |
| [📋 ComplianceCopilotAI](https://github.com/SpecterBreach/ComplianceCopilotAI) | AI GRC copilot for NIST 800-53, CIS, ISO 27001, FedRAMP. | ![](https://img.shields.io/github/stars/SpecterBreach/ComplianceCopilotAI?style=flat-square&color=FF6600) |

---

### 🔴 Red Team Tools

| Repo | Description | Stars |
|---|---|---|
| [☁️ CloudRaider](https://github.com/SpecterBreach/CloudRaider) | MITRE ATT&CK mapped cloud attack simulation. OCI · AWS · Azure purple team scenarios. | ![](https://img.shields.io/github/stars/SpecterBreach/CloudRaider?style=flat-square&color=D62828) |
| [💉 IMDSThief](https://github.com/SpecterBreach/IMDSThief) | Multi-cloud IMDS credential theft demo. OCI · AWS IMDSv1/v2 · Azure. Educational with defensive mitigations. | ![](https://img.shields.io/github/stars/SpecterBreach/IMDSThief?style=flat-square&color=D62828) |
| [🔑 JWTAnalyzer](https://github.com/SpecterBreach/JWTAnalyzer) | Cloud JWT token weakness detector. AWS Cognito · Azure AD · OCI IDCS. | ![](https://img.shields.io/github/stars/SpecterBreach/JWTAnalyzer?style=flat-square&color=D62828) |

---

### 🔵 Blue Team & Defensive Tools

| Repo | Description | Stars |
|---|---|---|
| [📊 SIEMForge](https://github.com/SpecterBreach/SIEMForge) | Cloud log normalizer. OCI Audit · AWS CloudTrail · Azure Monitor → ECS format for any SIEM. | ![](https://img.shields.io/github/stars/SpecterBreach/SIEMForge?style=flat-square&color=004080) |
| [✅ SecBaseline](https://github.com/SpecterBreach/SecBaseline) | CIS Level 1 & 2 benchmark auto-checker with delta tracking. PDF + Excel output. | ![](https://img.shields.io/github/stars/SpecterBreach/SecBaseline?style=flat-square&color=004080) |
| [🏷️ VCN-SecurityAudit](https://github.com/SpecterBreach/VCN-SecurityAudit) | OCI VCN security list and NSG auditor. All regions. Auto-generates Terraform fix for open rules. | ![](https://img.shields.io/github/stars/SpecterBreach/VCN-SecurityAudit?style=flat-square&color=004080) |

---

### 🧠 AI Security Tools

| Repo | Description | Stars |
|---|---|---|
| [🤖 ThreatModelAI](https://github.com/SpecterBreach/ThreatModelAI) | AI threat modeling from architecture diagrams. STRIDE + PASTA. Attack trees + MITRE mappings. | ![](https://img.shields.io/github/stars/SpecterBreach/ThreatModelAI?style=flat-square&color=9B5DE5) |
| [💬 CVEChat](https://github.com/SpecterBreach/CVEChat) | Chat interface over live NVD/CISA KEV. Ask security questions in plain English. | ![](https://img.shields.io/github/stars/SpecterBreach/CVEChat?style=flat-square&color=9B5DE5) |
| [🎣 PhishSenseAI](https://github.com/SpecterBreach/PhishSenseAI) | LLM phishing email analyzer. Scores probability, extracts IOCs, generates training points. | ![](https://img.shields.io/github/stars/SpecterBreach/PhishSenseAI?style=flat-square&color=9B5DE5) |

---

### 📚 Education & Community

| Repo | Description | Stars |
|---|---|---|
| [📖 cloud-security-playbook](https://github.com/SpecterBreach/cloud-security-playbook) | Practitioner's cloud security reference — OCI · AWS · Azure · GCP. Threat hunting, IR, compliance, AI agents. | ![](https://img.shields.io/github/stars/SpecterBreach/cloud-security-playbook?style=flat-square&color=00C875) |
| [✅ cloud-security-checklist](https://github.com/SpecterBreach/cloud-security-checklist) | Hardening checklists for OCI · AWS · Azure · GCP with automation hooks to SpecterBreach tools. | ![](https://img.shields.io/github/stars/SpecterBreach/cloud-security-checklist?style=flat-square&color=00C875) |
| [🎓 cloudsec-interview-prep](https://github.com/SpecterBreach/cloudsec-interview-prep) | 500+ cloud security interview questions across OCI, AWS, Azure, GCP. | ![](https://img.shields.io/github/stars/SpecterBreach/cloudsec-interview-prep?style=flat-square&color=00C875) |

---

## `> cat contributing.md`

We welcome contributions from the community. Every tool here is open-source and MIT licensed.

```bash
git clone https://github.com/SpecterBreach/<repo-name>
cd <repo-name>
git checkout -b feature/your-contribution
# Make your changes then open a Pull Request → reviewed within 48 hours
```

---

<div align="center">

**Founded by [@nvsaigeetham](https://github.com/nvsaigeetham)**

[![GitHub](https://img.shields.io/badge/Follow_@nvsaigeetham-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nvsaigeetham)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/saigeetham)
[![Email](https://img.shields.io/badge/hello@specterbreach.io-FF6600?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@specterbreach.io)

```
// MIT Licensed · Built with ⚡ by the community · Star what you use
```

</div>
