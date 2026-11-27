<div align="center">

# Sean Kwon

Founder & CEO at **[SJK Systems, Inc.](https://sjksystems.com)**

Building safe multi-agent tools and open-source guardrails for AI coding agents.

[![Website](https://img.shields.io/badge/SJK_Systems-sjksystems.com-111827?style=flat-square)](https://sjksystems.com)
[![ForAgent](https://img.shields.io/badge/ForAgent-foragent.io-2563EB?style=flat-square)](https://foragent.io)
[![ClevAgent](https://img.shields.io/badge/ClevAgent-clevagent.io-059669?style=flat-square)](https://clevagent.io)
[![Discord](https://img.shields.io/badge/Discord-Community-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/v5KFPkn4ux)
[![X](https://img.shields.io/badge/X-@SeanJHKwon-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/SeanJHKwon)
[![Dev.to](https://img.shields.io/badge/Dev.to-seanjhkwon-0A0A0A?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/seanjhkwon)

</div>

---

## Products

| Product | What it does | Links |
| --- | --- | --- |
| **[ForAgent (foragent.io)](https://foragent.io)** | Private phone numbers that let AI agents call and collaborate across any setup, with owner approval. | [Website](https://foragent.io) · [Skills & MCP](https://github.com/seankwon816/foragent-skills) · [Examples](https://github.com/seankwon816/foragent-examples) |
| **[ClevAgent (clevagent.io)](https://clevagent.io)** | A multi-agent desktop workspace with built-in guardrails and audit. | [Website](https://clevagent.io) (pre-launch) |

### [ForAgent (foragent.io)](https://foragent.io)

Give every AI agent a private number so agents across apps, plugins, machines, or teams can call each other and share files on your approval.

- Works across native macOS and Windows apps as well as the hosted Remote MCP server (`https://foragent.io/mcp`).
- Every incoming call requires explicit human pickup approval, with approved contacts and built-in turn limits to prevent runaway loops.
- Connect in one click or install the official skill:

[![Add to Cursor](https://cursor.com/deeplink/mcp-install-dark.svg)](https://cursor.com/install-mcp?name=ForAgent&config=eyJ1cmwiOiJodHRwczovL2ZvcmFnZW50LmlvL21jcCJ9)
&nbsp;
[![Install in VS Code](https://img.shields.io/badge/Install_in-VS_Code-007ACC?style=for-the-badge)](https://vscode.dev/redirect/mcp/install?name=ForAgent&config=%7B%22type%22:%22http%22,%22url%22:%22https://foragent.io/mcp%22+%7D)

```bash
# Claude Code Remote MCP
claude mcp add --transport http foragent-remote https://foragent.io/mcp

# Agent skill
npx skills add seankwon816/foragent-skills
```

Explore runnable Python, TypeScript, and n8n integrations in **[seankwon816/foragent-examples](https://github.com/seankwon816/foragent-examples)**.

### [ClevAgent (clevagent.io)](https://clevagent.io)

The desktop workspace to run, orchestrate, and collaborate with AI agents safely, with local guardrails and audit built in.

- Combines multi-agent orchestration, agent teams, Lounge, a built-in browser, and scheduled workflows in one place.
- Pauses risky actions (credential exposure, destructive commands, unauthorized payments or deletions) locally for human review and exports structured audit records.
- Currently completing pre-launch work; check **[clevagent.io](https://clevagent.io)** for current status.

---

## Open-Source Guardrails & Field Notes

### [seankwon816/ai-coding-agent-tips](https://github.com/seankwon816/ai-coding-agent-tips)

Zero-dependency `.claude/` and `AGENTS.md` config auditor, drop-in starter rules, and doc-verified fixes for Claude Code, Codex, Cursor, and MCP.

```bash
# Run a read-only local config audit on any repo (Python 3 stdlib only)
curl -fsSL https://raw.githubusercontent.com/seankwon816/ai-coding-agent-tips/main/scripts/audit_agent_configs.py | python3 - .
```

---

## Community

- **[SJK Systems Discord](https://discord.gg/v5KFPkn4ux)**: Daily AI workflow tips, agent guardrails, and product discussions for ClevAgent and ForAgent.
