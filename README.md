## Deepak K

Product Manager, [Catalyst by Zoho](https://catalyst.zoho.com): serverless compute, hosting and data on Zoho's own infrastructure.

I work where coding agents meet cloud platforms. My focus is giving agents enough platform knowledge to write code that actually deploys, then verifying what they produce.

### Work

**[catalystbyzoho/agent-skills](https://github.com/catalystbyzoho/agent-skills)**: Agent Skills that teach Claude Code, Cursor, Copilot, Gemini CLI and Windsurf to build on Catalyst. I built it and maintain it.

- 18 skills covering the platform:
  - Functions (7 types, API Gateway, security rules)
  - AppSail (PaaS, Docker)
  - Slate (frontend hosting, SSR)
  - Data Store + ZCQL, NoSQL, Stratus object storage
  - Signals event bus, Cache, job scheduling
  - QuickML (LLM serving, RAG), Zia
  - SDKs for 7 runtimes
- Agent-driven infrastructure provisioning through Zoho MCP (`CatalystbyZoho_*` tools)
- A runnable eval suite in claude-plugin-eval format, with 29 cases targeting runtime-verified gotchas
- An audit pass that removed fabricated APIs and cross-skill contradictions
- Tiered reference files that fall back to live docs instead of shipping a docs dump

```bash
npx skills add catalystbyzoho/agent-skills
```
