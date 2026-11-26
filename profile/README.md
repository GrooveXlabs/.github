<!--
  GrooveXlabs is a personal GitHub User account, so the active profile homepage renders from:
  https://github.com/GrooveXlabs/GrooveXlabs/blob/main/README.md
-->

<div align="center">
  <a href="https://www.bhaaratxa.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GrooveXlabs/GrooveXlabs/main/assets/hero-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GrooveXlabs/GrooveXlabs/main/assets/hero-light.svg" />
      <img alt="Rohit Sharma — GrooveXlabs Principal Security Architect" src="https://raw.githubusercontent.com/GrooveXlabs/GrooveXlabs/main/assets/hero-dark.svg" width="100%" />
    </picture>
  </a>

  <br /><br />

  <a href="https://www.bhaaratxa.com">
    <img src="https://img.shields.io/badge/BhaaratXa_Platform-www.bhaaratxa.com-10B981?style=flat-square&labelColor=111114" alt="BhaaratXa Platform" />
  </a>
  <a href="https://www.bhaaratxa.com/security">
    <img src="https://img.shields.io/badge/Security_Posture-Strict_CSP_%C2%B7_RFC_9116-18181B?style=flat-square&labelColor=111114" alt="Security Posture" />
  </a>
  <a href="https://www.bhaaratxa.com/case-studies">
    <img src="https://img.shields.io/badge/Case_Studies-Cloud_%C2%B7_VAPT-18181B?style=flat-square&labelColor=111114" alt="Case Studies" />
  </a>
  <a href="mailto:contact@bhaaratxa.com">
    <img src="https://img.shields.io/badge/Advisory-contact%40bhaaratxa.com-18181B?style=flat-square&labelColor=111114" alt="Contact" />
  </a>
</div>

---

### Executive Overview

Principal Security Architect and founder building **[BhaaratXa Technologies](https://www.bhaaratxa.com)** — combining 4+ years of production cloud & enterprise systems engineering with enterprise Vulnerability Assessment and Penetration Testing (**Deloitte VAPT alumni**).

Open-source engineering under **GrooveXlabs** focuses on securing the Model Context Protocol (**MCP**) attack surface, closing the red-to-purple-to-blue detection loop, and hardening local-first AI developer runtimes.

---

### Ecosystem Architecture

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GrooveXlabs/GrooveXlabs/main/assets/architecture-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/GrooveXlabs/GrooveXlabs/main/assets/architecture-light.svg" />
    <img alt="GrooveXlabs Defense-in-Depth Security Topology" src="https://raw.githubusercontent.com/GrooveXlabs/GrooveXlabs/main/assets/architecture-dark.svg" width="100%" />
  </picture>
</div>

---

### Open-Source Security & Infrastructure Stack

#### 1. Zero-Trust MCP Security Suite
| Repository | Role | Core Capabilities | Status |
|---|---|---|---|
| **[groovewall](https://github.com/GrooveXlabs/groovewall)** | Runtime Firewall | Zero-trust proxy enforcing tool-call boundaries & policy gates for MCP servers | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/groovewall?style=flat-square&color=10B981&labelColor=111114&label=updated) |
| **[grooveguard](https://github.com/GrooveXlabs/grooveguard)** | Static Analyzer | Audits MCP manifests & codebases for SSRF, secret exposure, and CVE risks | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/grooveguard?style=flat-square&color=10B981&labelColor=111114&label=updated) |
| **[groovehub](https://github.com/GrooveXlabs/groovehub)** | Trust Registry | FastAPI registry auto-scoring MCP servers with GrooveGuard + MITRE / Sigma output | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/groovehub?style=flat-square&color=10B981&labelColor=111114&label=updated) |
| **[honeyclaw](https://github.com/GrooveXlabs/honeyclaw)** | Deception Canary | Traps and fingerprints unauthorized MCP clients and automated AI scrapers | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/honeyclaw?style=flat-square&color=10B981&labelColor=111114&label=updated) |

#### 2. Adversarial, Blue/Purple Team & Incident Engineering
| Repository | Domain | Engineering Scope | Status |
|---|---|---|---|
| **[groovestrike](https://github.com/GrooveXlabs/groovestrike)** | Penetration Testing | Autonomous MCP-native pentest loop from finding discovery to verified defense | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/groovestrike?style=flat-square&color=10B981&labelColor=111114&label=updated) |
| **[redtrack](https://github.com/GrooveXlabs/redtrack)** | Red Team Recon | Fast port enumeration, web fingerprinting, and MITRE ATT&CK attack-path mapping | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/redtrack?style=flat-square&color=10B981&labelColor=111114&label=updated) |
| **[purpleforge](https://github.com/GrooveXlabs/purpleforge)** | Detection Engineering | Bridges offensive findings into Sigma detections, Atomic Red Team tests & gap reports | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/purpleforge?style=flat-square&color=10B981&labelColor=111114&label=updated) |
| **[threathound](https://github.com/GrooveXlabs/threathound)** | Blue Team SOC | Windows event log hunting, IOC extraction, anomaly detection, and Sigma synthesis | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/threathound?style=flat-square&color=10B981&labelColor=111114&label=updated) |
| **[certin-sentinel](https://github.com/GrooveXlabs/certin-sentinel)** | Incident Compliance | Triage, MITRE ATT&CK classification & 6-hour CERT-In / DPDP reporting workflow | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/certin-sentinel?style=flat-square&color=10B981&labelColor=111114&label=updated) |
| **[forenchain](https://github.com/GrooveXlabs/forenchain)** | Digital Forensics | Cryptographic forensic evidence chain-of-custody ledger with integrity verification | ![Commit](https://img.shields.io/github/last-commit/GrooveXlabs/forenchain?style=flat-square&color=10B981&labelColor=111114&label=updated) |

#### 3. Resilient Runtime & AI Tooling Utilities
| Repository | Focus | Technical Summary |
|---|---|---|
| **[groovelink](https://github.com/GrooveXlabs/groovelink)** | API Resilience | Circuit-breaker, exponential retry, rate-limiting & health-check client library |
| **[groovefetch](https://github.com/GrooveXlabs/groovefetch)** | Structured Ingestion | Stealth Playwright extraction pipeline with strict schema validation for RAG |
| **[toolsmith-agent](https://github.com/GrooveXlabs/toolsmith-agent)** | Tool Research | Autonomous architecture evaluation with multi-gate verification workflow |
| **[bhaaratclaw](https://github.com/GrooveXlabs/bhaaratclaw)** | Local CLI Engine | Local-first Python autonomous CLI assistant & workflow runner |
| **[security-notes](https://github.com/GrooveXlabs/security-notes)** | AppSec Reference | Concise architecture notes across networking, Linux internals, cryptography & VAPT |

---

### Commercial Flagship — BhaaratXa Technologies

- **[BhaaratXa Platform (`bhaaratxa.com`)](https://www.bhaaratxa.com)** — Hardened, build-time prerendered Cloudflare Pages web presence enforcing HSTS preload, `script-src 'self'`, `X-Frame-Options: DENY`, WebGL 3D enclave visualization, and RFC 9116 vulnerability disclosure (`/.well-known/security.txt`).
- **Bhaaratxa Workforce (`v0.2.0`)** — Windows desktop AI engineering studio orchestrating isolated `bw/<agent>/<task>` Git worktrees, tri-engine execution (`NativeApiRunner`, ConPTY `OpenCodePtyRunner`, `AgyRunner`), write-only Windows DPAPI `KeyVault`, OTLP span budgets, and offline Ed25519 licensing.

---

### Core Engineering Stack & Security Standards

- **Application & Runtime:** `TypeScript`, `Python`, `Electron`, `React`, `PixiJS`, `FastAPI`, `Playwright`, `Node.js`
- **Cloud & Security:** `AWS (IAM, VPC, WAF, CloudWatch)`, `Cloudflare Pages`, `OWASP Top 10`, `CVSS v3.1`, `MITRE ATT&CK`, `Sigma`, `Atomic Red Team`
- **Core Invariants:** Zero-trust input boundaries (`Zod` / schema-strict), write-only OS credential custody (`DPAPI`), SSRF allowlisting, and immutable audit trails.

---

<div align="center">
  <sub>
    <strong>Rohit Sharma</strong> · Principal Security Architect &amp; Founder, <a href="https://www.bhaaratxa.com">BhaaratXa Technologies</a> ·
    <a href="mailto:contact@bhaaratxa.com">contact@bhaaratxa.com</a> ·
    <a href="https://www.bhaaratxa.com/.well-known/security.txt">security.txt</a>
  </sub>
</div>