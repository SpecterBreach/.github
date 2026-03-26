<div align="center">

```
 ██████╗██╗   ██╗██████╗ ███████╗██████╗  █████╗ ██╗
██╔════╝╚██╗ ██╔╝██╔══██╗██╔════╝██╔══██╗██╔══██╗██║
██║      ╚████╔╝ ██████╔╝█████╗  ██████╔╝███████║██║
██║       ╚██╔╝  ██╔══██╗██╔══╝  ██╔══██╗██╔══██║██║
╚██████╗   ██║   ██████╔╝███████╗██║  ██║██║  ██║██║
 ╚═════╝   ╚═╝   ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝

 █████╗  ██████╗ ███████╗███╗   ██╗ ██████╗██╗   ██╗
██╔══██╗██╔════╝ ██╔════╝████╗  ██║██╔════╝╚██╗ ██╔╝
███████║██║  ███╗█████╗  ██╔██╗ ██║██║      ╚████╔╝
██╔══██║██║   ██║██╔══╝  ██║╚██╗██║██║       ╚██╔╝
██║  ██║╚██████╔╝███████╗██║ ╚████║╚██████╗   ██║
╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═══╝ ╚═════╝   ╚═╝
```

### `"Offensive Intelligence. Defensive Automation."`

Open-source security tools for cloud security professionals · Built by practitioners · Used in the field

[![Repos](https://img.shields.io/badge/Repos-38-4D148C?style=for-the-badge&logoColor=white)](https://github.com/orgs/CyberAI-Agency/repositories)
[![AI Agents](https://img.shields.io/badge/AI_Security_Agents-8-FF6600?style=for-the-badge&logoColor=white)](https://github.com/CyberAI-Agency/CyberOpsOrchestrator)
[![Clouds](https://img.shields.io/badge/Clouds-OCI_·_AWS_·_Azure_·_GCP-00D4FF?style=for-the-badge&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-00C875?style=for-the-badge&logoColor=white)](#)

</div>

---

## `> cat mission.txt`

```
CyberAI Agency builds open-source security tools for cloud security professionals.

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
| [🐐 CloudGoat-OCI](https://github.com/CyberAI-Agency/CloudGoat-OCI) | **FLAGSHIP** — Vulnerable-by-design OCI environment. 8 CTF scenarios: IAM privesc, IDCS takeover, IMDS theft, VCN escape, Cloud Guard bypass, PAR abuse. First OCI equivalent of Rhino Security's CloudGoat. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CloudGoat-OCI?style=flat-square&color=4D148C) |
| [🛡️ CloudSentinel](https://github.com/CyberAI-Agency/CloudSentinel) | Multi-cloud IAM auditor for OCI · AWS · Azure · GCP. Detects non-federated users, MFA gaps, overpermissioned policies, stale credentials. AI remediation scripts included. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CloudSentinel?style=flat-square&color=4D148C) |
| [🔍 CSPMlite](https://github.com/CyberAI-Agency/CSPMlite) | Lightweight open-source CSPM dashboard. CIS benchmark auto-checker with React UI and persistent finding history. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CSPMlite?style=flat-square&color=4D148C) |
| [🏷️ TagHunter](https://github.com/CyberAI-Agency/TagHunter) | Cross-cloud resource tag compliance scanner. Identifies untagged, mis-tagged resources. Supports EAI tag frameworks. | ![](https://img.shields.io/github/stars/CyberAI-Agency/TagHunter?style=flat-square&color=4D148C) |
| [🔐 MFAWatch](https://github.com/CyberAI-Agency/MFAWatch) | Identity audit tool flagging MFA gaps across cloud IAM users. OCI Classic IAM + IDCS, AWS, Azure. AI-generated remediation emails. | ![](https://img.shields.io/github/stars/CyberAI-Agency/MFAWatch?style=flat-square&color=4D148C) |
| [📊 PolicyScorer](https://github.com/CyberAI-Agency/PolicyScorer) | IAM policy risk scoring engine. Wildcard detector, cross-account trust graph, AI explanation of risky statements. | ![](https://img.shields.io/github/stars/CyberAI-Agency/PolicyScorer?style=flat-square&color=4D148C) |
| [🕸️ OCIAttackGraph](https://github.com/CyberAI-Agency/OCIAttackGraph) | OCI privilege escalation path mapper using Neo4j. Finds shortest path to admin across all IAM policies in a tenancy. | ![](https://img.shields.io/github/stars/CyberAI-Agency/OCIAttackGraph?style=flat-square&color=4D148C) |
| [🔄 CloudDriftDetector](https://github.com/CyberAI-Agency/CloudDriftDetector) | Detects config drift between Terraform IaC and live cloud state. Alerts on unauthorized manual changes. OCI · AWS · Azure. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CloudDriftDetector?style=flat-square&color=4D148C) |
| [🔑 SecretScannerAI](https://github.com/CyberAI-Agency/SecretScannerAI) | AI-powered cloud storage secret scanner. Finds hardcoded keys, tokens, passwords in OCI Object Storage, S3, Azure Blob. LLM validation cuts false positives. | ![](https://img.shields.io/github/stars/CyberAI-Agency/SecretScannerAI?style=flat-square&color=4D148C) |

---

### 🤖 AI Security Agents

> Autonomous security agents built on Claude. Each agent is independently deployable and connects to the CyberOpsOrchestrator.

| Agent | Mission | Stars |
|---|---|---|
| [⚡ CyberOpsOrchestrator](https://github.com/CyberAI-Agency/CyberOpsOrchestrator) | **Master coordinator** — routes security tasks to specialist agents, manages parallel execution, aggregates findings into unified reports. The AI CISO. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CyberOpsOrchestrator?style=flat-square&color=FF6600) |
| [🛡️ CloudGuardianAI](https://github.com/CyberAI-Agency/CloudGuardianAI) | 24/7 autonomous cloud posture monitor. Detects misconfigs → generates Terraform fixes → alerts via Slack/Teams → creates Jira tickets. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CloudGuardianAI?style=flat-square&color=FF6600) |
| [🔍 ThreatHunterAI](https://github.com/CyberAI-Agency/ThreatHunterAI) | AI-driven SIEM threat hunting. Hunts for IOCs, lateral movement, anomalies. 100% MITRE ATT&CK mapped. ELK · Splunk · Sentinel. | ![](https://img.shields.io/github/stars/CyberAI-Agency/ThreatHunterAI?style=flat-square&color=FF6600) |
| [🔴 PenTestAgentAI](https://github.com/CyberAI-Agency/PenTestAgentAI) | Autonomous red team agent with strict scope enforcement and human approval gates. Recon → vuln ID → pentest report. | ![](https://img.shields.io/github/stars/CyberAI-Agency/PenTestAgentAI?style=flat-square&color=FF6600) |
| [🕸️ IAMAnalyzerAI](https://github.com/CyberAI-Agency/IAMAnalyzerAI) | IAM privilege escalation path agent. Neo4j graph across OCI · AWS · Azure. Finds shadow admins and attack paths automatically. | ![](https://img.shields.io/github/stars/CyberAI-Agency/IAMAnalyzerAI?style=flat-square&color=FF6600) |
| [🚨 SOCAnalystAI](https://github.com/CyberAI-Agency/SOCAnalystAI) | AI L1 SOC analyst. Triages alerts → enriches with VirusTotal/Shodan → determines severity → creates Jira/ServiceNow tickets. | ![](https://img.shields.io/github/stars/CyberAI-Agency/SOCAnalystAI?style=flat-square&color=FF6600) |
| [📰 CVEResearcherAI](https://github.com/CyberAI-Agency/CVEResearcherAI) | 24/7 CVE monitoring + AI enrichment + multi-platform auto-publishing. NVD → Claude → LinkedIn · Reddit · X · Discord · Telegram. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CVEResearcherAI?style=flat-square&color=FF6600) |
| [📋 ComplianceCopilotAI](https://github.com/CyberAI-Agency/ComplianceCopilotAI) | AI GRC copilot for NIST 800-53, CIS, ISO 27001, FedRAMP. Gap analysis, policy templates, audit evidence narratives. | ![](https://img.shields.io/github/stars/CyberAI-Agency/ComplianceCopilotAI?style=flat-square&color=FF6600) |

---

### 🔴 Red Team Tools

| Repo | Description | Stars |
|---|---|---|
| [☁️ CloudRaider](https://github.com/CyberAI-Agency/CloudRaider) | MITRE ATT&CK mapped cloud attack simulation. Safe, scoped scenarios for OCI · AWS · Azure purple team exercises. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CloudRaider?style=flat-square&color=D62828) |
| [💉 IMDSThief](https://github.com/CyberAI-Agency/IMDSThief) | Multi-cloud IMDS credential theft demo. OCI · AWS IMDSv1/v2 · Azure IMDS. Educational — includes defensive mitigations. | ![](https://img.shields.io/github/stars/CyberAI-Agency/IMDSThief?style=flat-square&color=D62828) |
| [🔑 JWTAnalyzer](https://github.com/CyberAI-Agency/JWTAnalyzer) | Cloud JWT token weakness detector. Algorithm confusion, weak secrets, missing claims. AWS Cognito · Azure AD · OCI IDCS. | ![](https://img.shields.io/github/stars/CyberAI-Agency/JWTAnalyzer?style=flat-square&color=D62828) |

---

### 🔵 Blue Team & Defensive Tools

| Repo | Description | Stars |
|---|---|---|
| [📊 SIEMForge](https://github.com/CyberAI-Agency/SIEMForge) | Cloud log normalizer. Converts OCI Audit, AWS CloudTrail, Azure Monitor logs to ECS format for ELK/Splunk. One-command pipeline. | ![](https://img.shields.io/github/stars/CyberAI-Agency/SIEMForge?style=flat-square&color=004080) |
| [✅ SecBaseline](https://github.com/CyberAI-Agency/SecBaseline) | CIS Level 1 & 2 benchmark auto-checker. Generates delta reports between scans. PDF + Excel output. Multi-cloud. | ![](https://img.shields.io/github/stars/CyberAI-Agency/SecBaseline?style=flat-square&color=004080) |
| [🏷️ VCN-SecurityAudit](https://github.com/CyberAI-Agency/VCN-SecurityAudit) | OCI VCN security list and NSG auditor. Cross-compartment, all regions. Auto-generates Terraform fix for open rules. | ![](https://img.shields.io/github/stars/CyberAI-Agency/VCN-SecurityAudit?style=flat-square&color=004080) |

---

### 🧠 AI Security Tools

| Repo | Description | Stars |
|---|---|---|
| [🤖 ThreatModelAI](https://github.com/CyberAI-Agency/ThreatModelAI) | AI threat modeling from architecture diagrams. STRIDE + PASTA. Outputs attack trees + MITRE mappings + recommended controls. | ![](https://img.shields.io/github/stars/CyberAI-Agency/ThreatModelAI?style=flat-square&color=9B5DE5) |
| [💬 CVEChat](https://github.com/CyberAI-Agency/CVEChat) | Chat interface over live NVD/CISA KEV. Ask: "What critical OCI vulns dropped this week?" in plain English. | ![](https://img.shields.io/github/stars/CyberAI-Agency/CVEChat?style=flat-square&color=9B5DE5) |
| [🎣 PhishSenseAI](https://github.com/CyberAI-Agency/PhishSenseAI) | LLM phishing email analyzer. Scores probability, extracts IOCs, identifies techniques, generates user training points. | ![](https://img.shields.io/github/stars/CyberAI-Agency/PhishSenseAI?style=flat-square&color=9B5DE5) |

---

### 📚 Education & Community

| Repo | Description | Stars |
|---|---|---|
| [⭐ awesome-cloud-sec](https://github.com/CyberAI-Agency/awesome-cloud-sec) | Curated list of cloud security tools, frameworks, blogs, certifications, and learning resources. Updated weekly. | ![](https://img.shields.io/github/stars/CyberAI-Agency/awesome-cloud-sec?style=flat-square&color=00C875) |
| [📋 oci-security-checklist](https://github.com/CyberAI-Agency/oci-security-checklist) | Comprehensive OCI security hardening checklist. IAM, VCN, compute, storage, logging. The definitive OCI hardening reference. | ![](https://img.shields.io/github/stars/CyberAI-Agency/oci-security-checklist?style=flat-square&color=00C875) |
| [🎓 cloudsec-interview-prep](https://github.com/CyberAI-Agency/cloudsec-interview-prep) | 500+ cloud security interview questions covering IAM, CSPM, IR, architecture across AWS, Azure, OCI, GCP. | ![](https://img.shields.io/github/stars/CyberAI-Agency/cloudsec-interview-prep?style=flat-square&color=00C875) |

---

## `> cat threat_intel_site.txt`

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   🌐  CYBERAI THREAT INTELLIGENCE PORTAL                           │
│                                                                     │
│   Live CVE feed · AI-powered summaries · Cloud-specific advisories  │
│   Auto-published to LinkedIn · Reddit · X · Discord · Telegram      │
│                                                                     │
│   → cyberai.agency  (coming soon)                                  │
│   → github.com/CyberAI-Agency/cyberai-threat-intel                │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

## `> cat contributing.md`

We welcome contributions from the community. Every tool here is open-source and MIT licensed.

```bash
# Pick an issue labeled "good first issue" or "help wanted"
git clone https://github.com/CyberAI-Agency/<repo-name>
cd <repo-name>
git checkout -b feature/your-contribution

# Make your changes, then:
git push origin feature/your-contribution
# Open a Pull Request → we review within 48 hours
```

**Ways to contribute:**
- 🐛 Report bugs or security issues
- 🌟 Add new CloudGoat-OCI scenarios
- 🤖 Build new AI agent integrations
- 📝 Write documentation or walkthroughs
- ⭐ Star repos you find useful

---

## `> cat stack.txt`

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle_OCI-F80000?style=flat-square&logo=oracle&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-FF6600?style=flat-square&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

</div>

---

<div align="center">

**Founded by [@nvsaigeetham](https://github.com/nvsaigeetham)**

[![GitHub](https://img.shields.io/badge/Follow_@nvsaigeetham-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nvsaigeetham)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/saigeetham)
[![Email](https://img.shields.io/badge/hello@cyberai.agency-FF6600?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@cyberai.agency)

```
// MIT Licensed · Built with ⚡ by the community · Star what you use
```

</div>
