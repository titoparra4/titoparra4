<h1 align="center">Tito Parra</h1>

<h3 align="center">AI Product Management & Digital Strategy | Senior Technical Product Owner LATAM</h3>

<p align="center"><em>Engineering background. Product mindset. Business impact.</em></p>

<p align="center">📍 Madrid, Spain · 🌎 LATAM Experience · 🤖 Applied AI &amp; Automation</p>

<p align="center">
  <a href="https://titoparra.com">Website</a> ·
  <a href="https://linkedin.com/in/titoparra/">LinkedIn</a> ·
  <a href="https://github.com/titoparra4">GitHub</a>
</p>

---

## About Me

I'm a Senior Product Management and Software Engineer with **17+ years of experience** in technology, combining hands-on software engineering, technical leadership, and digital product management.

My career has evolved from building enterprise applications with .NET, C#, SQL, and Angular to leading complex digital initiatives, API ecosystems, and cross-functional teams across Latin America.

I specialize in connecting business strategy, product execution, software architecture, and applied artificial intelligence to deliver scalable, measurable business outcomes.

My experience spans insurance, retail, healthcare, and enterprise technology environments.

**What defines my approach:**

- **Product Leadership:** Strategy, discovery, roadmaps, backlog prioritization, stakeholder alignment, and end-to-end delivery.
- **Applied AI:** Integrating generative AI and LLMs into product workflows, documentation, requirements analysis, and operational processes.
- **Technical Expertise:** Enterprise APIs, cloud platforms, system integration, automation, and software engineering.
- **Regional Leadership:** Coordinating multidisciplinary teams and digital initiatives across multiple LATAM markets.
- **Business Impact:** Translating technical complexity into practical solutions that improve efficiency, scalability, and business value.

## Impact at Scale

| 17+ Years | 8 Countries | 50+ Partners | $1M USD |
|:---:|:---:|:---:|:---:|
| Technology Experience | LATAM Operations | API Integrations | Budget Managed |

| 15 Initiatives | ~20% | ~10% |
|:---:|:---:|:---:|
| Concurrent Portfolio | Cloud Cost Reduction | Budget Optimization |

<sub>Selected professional achievements from enterprise technology and digital product initiatives.</sub>

## Core Expertise

| Domain | Expertise |
|---|---|
| **Product Management** | Product Strategy, Discovery, Roadmaps, OKRs, Prioritization, Delivery |
| **Artificial Intelligence** | Generative AI, LLMs, Prompt Engineering, AI-Assisted Workflows |
| **Software Engineering** | C#, .NET, Angular, SQL, REST APIs, Enterprise Integrations |
| **Cloud & Architecture** | Microsoft Azure, Cosmos DB, API Architecture, Cloud Optimization |
| **Agile Leadership** | Scrum, Stakeholder Management, Cross-Functional Teams |
| **Digital Transformation** | Process Automation, Modernization, Operational Efficiency |

## Technology Ecosystem

**Software Development**
`C#` `.NET` `ASP.NET Core` `Angular` `JavaScript` `SQL Server`

**Cloud, Data & Integration**
`Microsoft Azure` `Azure DevOps` `Cosmos DB` `REST APIs` `SOAP` `Postman`

**AI & Productivity**
`ChatGPT` `Claude` `Generative AI` `LLMs` `Prompt Engineering` `AI-Assisted Workflows`

**Product & Delivery**
`Product Discovery` `Roadmapping` `Scrum` `Design Thinking` `API Product Management` `Technical Leadership`

## What I'm Building & Exploring

I'm particularly interested in creating reusable tools, open-source resources, and AI-powered workflows that help teams work more effectively.

Current areas of exploration include:

- **AI-Powered Software Engineering:** Practical AI workflows for development, testing, and documentation.
- **Intelligent Quality Engineering:** AI-assisted test strategies, regression testing, and API validation.
- **Secure Development:** Code review, vulnerability assessment, and security-focused engineering workflows.
- **AI Skills & Automation:** Reusable AI capabilities for ChatGPT, Claude, and developer environments.
- **Technical Product Management:** Bringing structure, automation, and intelligence to product discovery and delivery.

## Featured Open Source Projects

Open-source [Agent Skills](https://agentskills.io) (`SKILL.md` format) that work with Claude Code, OpenAI Codex and other compatible AI assistants.

### 🛡️ [Secure Code Reviewer](https://github.com/titoparra4/secure-code-reviewer)

[![Release](https://img.shields.io/badge/release-v1.0.0-blue?style=flat-square)](https://github.com/titoparra4/secure-code-reviewer/releases)
![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Python 3.9+](https://img.shields.io/badge/python-3.9%2B-blue?style=flat-square)

Evidence-based security code review for source code, secrets, dependencies, APIs and infrastructure-as-code. Every finding is tied to a file and line, with sanitized evidence, calibrated severity, a fix and a regression test. Includes offline, dependency-free tooling that produces JSON, Markdown and SARIF reports.

**Install**

```bash
# Any compatible agent (skills.sh CLI)
npx skills add titoparra4/secure-code-reviewer

# Claude Code (personal skill)
git clone --depth 1 --branch v1.0.0 https://github.com/titoparra4/secure-code-reviewer.git \
  ~/.claude/skills/secure-code-reviewer
```

**Usage**

```text
Review this repository for security vulnerabilities.
Check this pull request for security risks.
Find exposed secrets.
Review my .NET APIs for OWASP vulnerabilities.
```

```bash
# Command line: offline scan + SARIF report
python3 scripts/scan_repository.py /path/to/repo --mode full -o /tmp/scr-raw.json
python3 scripts/normalize_findings.py /tmp/scr-raw.json -o /tmp/scr-report.json
python3 scripts/generate_report.py /tmp/scr-report.json -f sarif -o /tmp/scr-report.sarif
```

### 🧪 [Intelligent QA Engineer](https://github.com/titoparra4/intelligent-qa-engineer)

[![Release](https://img.shields.io/badge/release-v0.1.0-blue?style=flat-square)](https://github.com/titoparra4/intelligent-qa-engineer/releases)
![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

Turns user stories, requirements, OpenAPI contracts and code changes into risk-based test strategies, traceable test cases, negative and edge scenarios, runnable API automation (Postman/Newman, pytest, Playwright, Jest/Vitest), regression plans and QA reports. Works in English and Spanish.

**Install**

```bash
# Any compatible agent (skills.sh CLI)
npx skills add titoparra4/intelligent-qa-engineer
```

```text
# Claude Code plugin marketplace
/plugin marketplace add titoparra4/intelligent-qa-engineer
/plugin install intelligent-qa-engineer@intelligent-qa-engineer
```

**Usage**

```text
Analyze this user story and generate test cases.
Generate Postman tests from this OpenAPI specification.
Build a regression test plan for this pull request.
Analiza esta historia de usuario y genera casos de prueba negativos.
```

```text
# Explicit invocation in Claude Code
/intelligent-qa-engineer REGRESSION for the current git diff
```

> My focus is not AI for the sake of AI. It's building useful, reliable solutions that solve real problems.
