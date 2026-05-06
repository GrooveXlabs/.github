<!-- GROOVEXLABS PROFILE README -->
<!-- Designed for maximum visual impact -->

<div align="center">

<!-- Animated SVG Banner -->
<svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="gx-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0f0c29;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#302b63;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#24243e;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="text-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#7b2cbf;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ff006e;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="100%" height="200" fill="url(#gx-grad)" rx="12"/>
  
  <!-- Circuit pattern -->
  <g stroke="#00d4ff" stroke-width="0.5" opacity="0.15">
    <path d="M50,180 L50,150 L80,150 L80,120 M700,20 L700,50 L670,50 L670,80"/>
    <circle cx="50" cy="180" r="3" fill="#00d4ff"/>
    <circle cx="700" cy="20" r="3" fill="#ff006e"/>
    <path d="M100,30 L130,30 L130,60 L160,60 M600,170 L570,170 L570,140 L540,140"/>
  </g>
  
  <!-- Main Title -->
  <text x="400" y="85" text-anchor="middle" font-family="monospace" font-size="42" font-weight="bold" fill="url(#text-grad)" filter="url(#glow)">GrooveXlabs</text>
  
  <!-- Tagline -->
  <text x="400" y="125" text-anchor="middle" font-family="monospace" font-size="16" fill="#a8a8b3" letter-spacing="3">SECURITY-FIRST AI TOOLING ECOSYSTEM</text>
  
  <!-- Animated dots -->
  <circle cx="340" cy="155" r="4" fill="#00d4ff" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="400" cy="155" r="4" fill="#7b2cbf" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="460" cy="155" r="4" fill="#ff006e" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2s" begin="1.2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br>

<!-- Typing Effect -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Building+the+future+of+AI+infrastructure;Security-first+by+design;MCP-native+tooling+ecosystem;Open+source.+Open+minds." alt="Typing SVG" />

<br><br>

<!-- Badges Row -->
<a href="https://github.com/GrooveXlabs">
  <img src="https://img.shields.io/badge/Security-First-ff006e?style=for-the-badge&logo=shield&logoColor=white&labelColor=0f0c29" />
</a>
<a href="https://github.com/GrooveXlabs">
  <img src="https://img.shields.io/badge/MCP-Native-00d4ff?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAyTDQgN3YxMGw4IDUgOC01Vjd6bTAgMmwyIDF2NGwtMi0xLTIgMXYtNHptMCA4bDIgMXY0bC0yIDEtMi0xdi00eiIvPjwvc3ZnPg==&labelColor=0f0c29" />
</a>
<a href="https://github.com/GrooveXlabs">
  <img src="https://img.shields.io/badge/Open%20Source-Always-7b2cbf?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=0f0c29" />
</a>
<a href="https://github.com/GrooveXlabs">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0f0c29" />
</a>

</div>

<br>

---

## 🧬 The GrooveXlabs Ecosystem

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 🔒 GrooveGuard
**MCP Server Security Scanner**

```
┌─────────────────────────────────────────┐
│  SECRETS  │  SSRF  │  VALIDATION  │  CVE │
└─────────────────────────────────────────┘
```

[![GrooveGuard](https://img.shields.io/badge/v0.2.0-Ready-00d4ff?style=flat-square&logo=shield&logoColor=white&labelColor=1a1a2e)](https://github.com/GrooveXlabs/grooveguard)
[![Tests](https://img.shields.io/badge/Tests-61%2F61%20Passing-00ff88?style=flat-square&labelColor=1a1a2e)](https://github.com/GrooveXlabs/grooveguard)

Static analysis for MCP servers. Detects secrets, dangerous capabilities, SSRF risks, manifest misconfigurations, and dependency CVEs.

**→** [github.com/GrooveXlabs/grooveguard](https://github.com/GrooveXlabs/grooveguard)

</td>
<td width="50%" valign="top">

### 🌐 GrooveFetch
**AI-Native Adaptive Web Scraper**

```
┌─────────────────────────────────────────┐
│  STEALTH  │  ADAPT  │  SCHEMA  │  RAG  │
└─────────────────────────────────────────┘
```

[![GrooveFetch](https://img.shields.io/badge/v0.1.1-Ready-ff006e?style=flat-square&logo=spider&logoColor=white&labelColor=1a1a2e)](https://github.com/GrooveXlabs/groovefetch)
[![Tests](https://img.shields.io/badge/Tests-12%2F12%20Passing-00ff88?style=flat-square&labelColor=1a1a2e)](https://github.com/GrooveXlabs/groovefetch)

Stealth browsing with per-domain adaptive learning, schema validation, and built-in RAG pipeline.

**→** [github.com/GrooveXlabs/groovefetch](https://github.com/GrooveXlabs/groovefetch)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔗 GrooveLink
**Resilient API Client**

```
┌─────────────────────────────────────────┐
│  CIRCUIT  │  RETRY  │  RATE  │  HEALTH │
└─────────────────────────────────────────┘
```

[![GrooveLink](https://img.shields.io/badge/v0.1.0-Ready-7b2cbf?style=flat-square&logo=link&logoColor=white&labelColor=1a1a2e)](https://github.com/GrooveXlabs/groovelink)
[![Tests](https://img.shields.io/badge/Tests-40%2F40%20Passing-00ff88?style=flat-square&labelColor=1a1a2e)](https://github.com/GrooveXlabs/groovelink)

Production-grade API client with circuit breaker, exponential retry, rate limiting, and health checks.

**→** [github.com/GrooveXlabs/groovelink](https://github.com/GrooveXlabs/groovelink)

</td>
<td width="50%" valign="top">

### 🛠️ ToolSmith
**Autonomous Tool Discovery Agent**

```
┌─────────────────────────────────────────┐
│  DISCOVER  │  ANALYZE  │  BUILD  │  SHIP │
└─────────────────────────────────────────┘
```

[![ToolSmith](https://img.shields.io/badge/Agent-Active-00d4ff?style=flat-square&logo=robot&logoColor=white&labelColor=1a1a2e)](https://github.com/GrooveXlabs/toolsmith-agent)

Discovers trending dev tools, analyzes architecture, and builds improved alternatives. 5-gate gstack review pipeline.

**→** [github.com/GrooveXlabs/toolsmith-agent](https://github.com/GrooveXlabs/toolsmith-agent)

</td>
</tr>
</table>

</div>

---

## 📊 Ecosystem Metrics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=GrooveXlabs&show_icons=true&theme=radical&hide_border=true&bg_color=0f0c29&title_color=00d4ff&text_color=a8a8b3&icon_color=ff006e&count_private=true" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=GrooveXlabs&theme=radical&hide_border=true&background=0f0c29&stroke=00d4ff&ring=ff006e&fire=ff006e&currStreakLabel=00d4ff&sideLabels=a8a8b3&currStreakNum=00d4ff&sideNums=a8a8b3" width="49%" />

<br><br>

<img src="https://github-profile-trophy.vercel.app/?username=GrooveXlabs&theme=radical&no-frame=true&no-bg=true&column=7&margin-w=10&margin-h=10" width="100%" />

</div>

---

## 🎯 Security-First Principles

<div align="center">

```
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
│   [1] NEVER TRUST INPUT          [2] LEAST PRIVILEGE    [3] DEFENSE DEPTH │
│                                                                            │
│   [4] PRIVACY BY DESIGN          [5] SECURE BY DEFAULT  [6] FAIL SECURELY │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

Every tool in the GrooveXlabs ecosystem is built with these six principles.

</div>

---

## 🌊 Contribution Activity

<div align="center">

<img src="https://raw.githubusercontent.com/GrooveXlabs/GrooveXlabs/output/github-contribution-grid-snake.svg" alt="Contribution Snake" />

</div>

---

## 🧰 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Native-00d4ff?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAyTDQgN3YxMGw4IDUgOC01Vjd6bTAgMmwyIDF2NGwtMi0xLTIgMXYtNHptMCA4bDIgMXY0bC0yIDEtMi0xdi00eiIvPjwvc3ZnPg==&logoColor=white)

</div>

---

## 🗺️ Repository Map

<div align="center">

| Repository | Description | Status | Language |
|---|---|---|---|
| 🔒 [grooveguard](https://github.com/GrooveXlabs/grooveguard) | MCP Server Security Scanner | `v0.2.0` | Python |
| 🌐 [groovefetch](https://github.com/GrooveXlabs/groovefetch) | AI-Native Adaptive Web Scraper | `v0.1.1` | Python |
| 🔗 [groovelink](https://github.com/GrooveXlabs/groovelink) | Resilient API Client | `v0.1.0` | Python |
| 🛠️ [toolsmith-agent](https://github.com/GrooveXlabs/toolsmith-agent) | Autonomous Tool Discovery Agent | `Active` | Python |
| 📚 [gstack-kimi](https://github.com/GrooveXlabs/gstack-kimi) | Kimi CLI Skills & Automation | `v1.0` | Markdown |
| 🛡️ [AI-SOC-Analyst](https://github.com/GrooveXlabs/AI-SOC-Analyst) | LLM-Powered SOC Log Analyzer | `v0.1` | Python |
| 🎣 [Phishing-Shield](https://github.com/GrooveXlabs/Phishing-Shield) | AI Browser Extension for Phishing Detection | `v0.1` | JavaScript |
| 🔐 [SecureCode-AI](https://github.com/GrooveXlabs/SecureCode-AI) | Pre-commit Security Code Review | `v0.1` | Python |
| 📰 [DarkBrief](https://github.com/GrooveXlabs/DarkBrief) | Threat Intelligence Aggregator | `v0.1` | Python |
| 🦀 [bhaaratclaw](https://github.com/GrooveXlabs/bhaaratclaw) | India's First CLAW | `v0.1` | Python |

</div>

---

<div align="center">

## 💬 Let's Build Together

<a href="https://github.com/GrooveXlabs">
  <img src="https://img.shields.io/badge/GitHub-GrooveXlabs-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=GrooveXlabs&color=ff006e&style=for-the-badge&label=Profile+Views" alt="Profile Views" />

<br>

<sub>🔒 Built with security in mind. Open source by conviction.</sub>

</div>
