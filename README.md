<div align="center">

# Hi, I'm Kumar Abhinav 👋

### AI Security Engineer · LLM & Agentic AI Security · SIEM Architecture

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=800&center=true&vCenter=true&width=600&lines=Securing+AI+systems+that+read+untrusted+data;Building+agentic+SIEM+for+multi-tenant+SOCs;Using+AI+to+make+security+operations+faster" alt="Typing SVG" /></a>

<p>
  <a href="https://kumar-abhinav17.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/abhinav-cybersec"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:singhkumaraniah@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://x.com/KumarAb63237204"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
</p>

</div>

---

## 🛡️ About Me

I'm a security engineer in a multi-client **MSSP SOC** at **ESDS Software Solution**, developing Agentic SIEM.

Alongside SOC work, I architected and led the build of **Swaraj Hansa**, an agentic, LLM-assisted, multi-tenant SIEM platform. Building it taught me how AI systems fail when they read untrusted data and call tools — and how to design the controls that stop that from happening.

That's the work I want to keep doing: **securing AI systems** and **using AI to make security operations faster**.

## 🎯 Currently Open To

- AI Security Engineering
- Detection & Response Engineering
- Security Consulting

📍 Bengaluru or remote

## 🧰 Tech Stack

**Languages & Engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**SIEM & Data Pipeline**

![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat-square&logo=wazuh&logoColor=white)
![IBM QRadar](https://img.shields.io/badge/IBM_QRadar-052FAD?style=flat-square&logo=ibm&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![Logstash](https://img.shields.io/badge/Logstash-005571?style=flat-square&logo=logstash&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**AI / LLM**

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Tool_Security-6E40C9?style=flat-square)
![OWASP LLM Top 10](https://img.shields.io/badge/OWASP-LLM_Top_10-000000?style=flat-square&logo=owasp&logoColor=white)

**Offensive Security**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square)
![Nessus](https://img.shields.io/badge/Nessus-00C176?style=flat-square)

## 🔐 Security Expertise

| Domain | Details |
|---|---|
| AI / LLM Security | Prompt injection (direct & indirect), MCP tool security, excessive agency, output validation, OWASP Top 10 for LLMs, MITRE ATLAS, NIST AI RMF |
| SIEM & SOC | Incident triage, root cause analysis, MITRE ATT&CK, threat intel (AbuseIPDB, VirusTotal), multi-client MSSP operations |
| Security Architecture | Multi-tenant isolation, Zero Trust, mTLS / PKI, IPsec, PostgreSQL RLS, least privilege, threat modelling, Microsoft MCRA & MCSB |
| Assessment | Web & Android app testing, OWASP Top 10, PTES |

## 🦢 Featured Project

### Swaraj Hansa — Agentic, Multi-Tenant SIEM for MSSPs

An AI-assisted SIEM designed end to end by me and built with AI coding agents under my own architecture and security design.

| Category | Details |
|---|---|
| Pipeline | Wazuh collectors → mTLS → Logstash → Kafka → normaliser → AI triage → PostgreSQL + OpenSearch → FastAPI (REST + WebSocket) → React console |
| AI Guardrails | Untrusted-log isolation in prompts • Control-char stripping & injection-phrase neutralisation • 2,000-char truncation • Fixed JSON verdict schema that fails safe to `NEEDS_REVIEW` |
| Agent Controls | Tenant-scoped MCP tools enforced server-side • Assistant can't disclose detection rules or override verdicts • Full audit log of prompts, responses & tool calls |
| Cost & Privacy | Deterministic risk scoring (severity, threat intel, ATT&CK) so the LLM runs only on high-risk alerts • Local inference via Ollama — no prompt data leaves the environment |
| Tenant Isolation | mTLS client identity (unknown clients dead-lettered) • Per-tenant OpenSearch indices • PostgreSQL row-level security • App-level scoping with dual-logged cross-tenant actions |
| Results | 105 raw alerts → ~18 incidents; 7/7 attack scenarios routed to the correct queue in end-to-end validation • Load-test harness ready for 100–5,000 EPS |

## 🛠️ Other Projects

| Project | What it does |
|---|---|
| [**siem-pulse**](https://github.com/abhinav7077/siem-pulse) | Open-source log source health monitor — finds devices that stopped sending logs to QRadar, Splunk, Sentinel, Elastic, FortiSIEM, Wazuh and more. Multi-client SOC/MSSP automation in Python. |
| [**bug-bounty-agent**](https://github.com/abhinav7077/bug-bounty-agent) | Local, human-in-the-loop bug bounty agent — automated recon + a 10-stage vulnerability-assessment pipeline on a local LLM (Ollama), with every risky action gated behind explicit human approval. |

## 💼 Experience

- **Security Analyst** — ESDS Software Solution Limited, Bengaluru · *Nov 2024 – Present*
- **Penetration Testing Intern** — CFSS (remote) · *Mar – Apr 2024*
- **Application Penetration Testing Intern** — CyberHost (remote) · *Aug – Sep 2023*

## 🎓 Education & Certifications

- 🎓 B.Tech, Computer Science & Engineering (Cyber Security) — Dayananda Sagar University, 2020–2024
- 📜 Microsoft Applied Skills: Design solutions with MCRA & MCSB
- 📜 Fortinet Certified Associate in Cybersecurity
- ⏳ CompTIA CySA+ (in progress)

## 🔭 Current Focus

```yaml
Securing:
  - LLM agents that read untrusted data
  - MCP tool permissions & tenant boundaries
Building:
  - Swaraj Hansa (production benchmarks next)
  - Open-source SOC automation
Learning:
  - CompTIA CySA+
  - LLM red-teaming & evaluation
```

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=abhinav7077&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abhinav7077&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=abhinav7077&theme=tokyonight&hide_border=true" />

</div>

---

<div align="center">

*"Every AI system that reads untrusted data is an attack surface. I build the controls that keep it safe."*

</div>
