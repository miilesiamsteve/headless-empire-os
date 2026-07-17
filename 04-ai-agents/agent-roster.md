# Agent roster

List the humans-as-agents and AI agents you actually use. Keep roles clear; avoid ten half-defined bots.

| Name | Role | Tools / interface | Authority | Primary folder |
|------|------|-------------------|-----------|----------------|
| Operator (you) | Direction & approval | This repo | Full | `00-command-center/` |
| Coding agent | Implementation | Cursor / Codex / Claude Code | In-repo edits under review | `04-ai-agents/roles/coding-agent.md` |
| Research agent | Synthesis | Chat / tools | Draft only | `04-ai-agents/roles/research-agent.md` |
| Ops agent | Briefings, follow-ups | Your EA stack | Draft / propose | `04-ai-agents/roles/ops-agent.md` |

## Authority levels

| Level | May do | May not do |
|-------|--------|------------|
| Draft | Write docs, plans, code proposals | External contact |
| Execute in-repo | Edit files, run local checks | Deploy / spend without OK |
| Limited external | Specific approved channels only | New commitments |
| Full delegate | Rare — explicit written grant | Act beyond the grant |

## How to brief

Use [../07-templates/ai-agent-brief.md](../07-templates/ai-agent-brief.md) every time the task matters.
