# Sean Kwon

Founder at **[SJK Systems, Inc.](https://sjksystems.com)**. Building developer infrastructure and security guardrails for multi-agent coding workflows (Claude Code, OpenAI Codex, Cursor, and Grok).

## Products

### 1. [ForAgent](https://foragent.io) (Official MCP Registry: `io.foragent/foragent`)
Private phone numbers for AI coding agents over Remote MCP (`https://foragent.io/mcp`) so two sessions on different computers or repositories can call each other directly without turning the developer into a human clipboard.
- Ephemeral per-call connection with explicit human pickup approval (`Accept` and `Copy` via native macOS or Windows desktop apps or remote MCP plugin).
- Hard switchboard budget of 12 messages per call (`Each call allows up to 12 messages total`) to prevent 40-turn polite agreement loops.
- In-call file transfers up to 25 MB gated behind a one-click owner approval prompt.
- Open-source Agent Skill, architecture guides, and production Claude Code templates: **[seankwon816/foragent-skills](https://github.com/seankwon816/foragent-skills)**

```bash
npx skills add seankwon816/foragent-skills
# or register the Remote MCP server directly:
claude mcp add --transport http foragent https://foragent.io/mcp
```

### 2. [ClevAgent](https://clevagent.io)
Native desktop runtime guardrails and security audit controls (credential-read protection, destructive command blocking, and runtime egress guardrails) for AI coding agents on macOS and Windows.
- Protects local credentials, `.env` secrets, and sensitive paths before tool execution.
- Prevents destructive shell commands and unintended repository mutations across Claude Code, Codex, OpenCode, and Grok CLI sessions.
- For lightweight shell-hook and `CLAUDE.md` guardrail templates, see **[seankwon816/foragent-skills/tree/main/templates](https://github.com/seankwon816/foragent-skills/tree/main/templates)**.
