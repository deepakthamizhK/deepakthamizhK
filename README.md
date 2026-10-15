<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Deepak K, Product Manager at Catalyst by Zoho. Coding agent → agent-skills → Zoho MCP → Catalyst">
</p>

I work where coding agents meet cloud platforms. My focus is giving agents enough platform knowledge to write code that actually deploys, then verifying what they produce.

---

### [catalystbyzoho/agent-skills](https://github.com/catalystbyzoho/agent-skills)

[![stars](https://img.shields.io/github/stars/catalystbyzoho/agent-skills?style=flat-square&color=0d1117&labelColor=30363d)](https://github.com/catalystbyzoho/agent-skills/stargazers)
[![license](https://img.shields.io/badge/license-Apache--2.0-0d1117?style=flat-square&labelColor=30363d)](https://github.com/catalystbyzoho/agent-skills/blob/main/LICENSE)
[![skills](https://img.shields.io/badge/skills-18-0d1117?style=flat-square&labelColor=30363d)](https://github.com/catalystbyzoho/agent-skills/tree/main/skills)
[![evals](https://img.shields.io/badge/eval_cases-29-0d1117?style=flat-square&labelColor=30363d)](https://github.com/catalystbyzoho/agent-skills)

Agent Skills that teach coding agents to build on Catalyst. I built it and maintain it.

| Layer | Coverage |
|---|---|
| Compute | Functions (7 types, API Gateway, security rules) · AppSail (PaaS, Docker) · Job Scheduling |
| Hosting | Slate (frontend, Git deploy, SSR) |
| Data | Data Store + ZCQL · NoSQL · Stratus object storage · Cache |
| Events | Signals (event bus, rules, webhooks) |
| AI / ML | QuickML (LLM serving, RAG, AutoML) · Zia |
| Platform | Auth + OAuth Connections · SDKs for 7 runtimes · CLI & environments · Pricing |
| Infra via MCP | Provisioning through Zoho MCP (`CatalystbyZoho_*` tools) |

- **Verified, not generated:** a runnable eval suite in claude-plugin-eval format, plus an audit pass that removed fabricated APIs and cross-skill contradictions
- **Lean by design:** tiered references that fall back to live docs instead of bundling a docs dump

**Works with**

![Claude Code](https://img.shields.io/badge/Claude_Code-0d1117?style=flat-square&logo=claude&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-0d1117?style=flat-square&logo=cursor&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/Copilot-0d1117?style=flat-square&logo=githubcopilot&logoColor=white)
![Gemini CLI](https://img.shields.io/badge/Gemini_CLI-0d1117?style=flat-square&logo=googlegemini&logoColor=white)
![Windsurf](https://img.shields.io/badge/Windsurf-0d1117?style=flat-square&logo=windsurf&logoColor=white)

```bash
npx skills add catalystbyzoho/agent-skills
```

---

### Builds

| Project | Notes | |
|---|---|---|
| [my-home-3D](https://github.com/deepakthamizhK/my-home-3D) | 3D house-plan prototype built with Claude | [live ↗](https://myhome3d.vercel.app) |

### Now

Eval-driven hardening of the skills: verifying SDK and REST contracts against live services, and region/data-center coverage.

---

<p>
  <a href="https://x.com/deepakThamizhK"><img src="https://img.shields.io/badge/@deepakThamizhK-0d1117?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  &nbsp;notes on agents, serverless and deployment
</p>
