# AGENTS.md

Instructions for AI agents working in a Headless Empire OS repository.

## Mission

Help the human operator run a clear daily and weekly cycle: priorities, capture, decisions, execution, knowledge, and optional public-safe communication. Optimize for **next useful action**, not abstract advice.

## Authority model

- The **human operator** owns judgment, priorities, external commitments, and disclosures.  
- Agents may draft, research, organize, implement in-repo changes, and propose next steps.  
- Agents must **not** contact people, post publicly, spend money, or make promises unless the human has explicitly granted that authority for the task.  
- Mark assumptions. Prefer questions only when a missing decision would materially change the result.

## Orient first

1. `QUICK-START.md` (new operators) or `00-command-center/TODAY.md`  
2. `00-command-center/WEEK.md`  
3. `00-command-center/NOW.md`  
4. `00-command-center/inbox.md`  
5. This file and `99-meta/operating-principles.md`  

## Folder map

| Path | Use |
|------|-----|
| `00-command-center/` | Current day, week, context, inbox |
| `01-planning/` | Cadence planning and reviews |
| `02-tasks-projects/` | Projects, backlog, waiting-for, delegated, decisions |
| `03-marketing-content/` | Ideas through published assets |
| `04-ai-agents/` | Roster, roles, prompts |
| `05-knowledge-base/` | Durable reference (treat carefully; may be sensitive) |
| `06-systems-sops/` | Repeatable processes |
| `07-templates/` | Copy, don’t overwrite casually |
| `08-archive/` | Stale or completed material |
| `09-team-ops/` | Human team operations |
| `99-meta/` | System design and changelog |
| `examples/` | Fictional samples only |

## Operating rules

- Prefer practical markdown artifacts: checklists, tables, owners, dates, next actions.  
- Use ISO dates: `YYYY-MM-DD`.  
- Use relative links between files.  
- Capture ambiguity in `inbox.md`; process into the right folder.  
- Archive under `08-archive/` instead of deleting history.  
- Put multi-step work in `02-tasks-projects/active/` with a short brief.  
- For delegated AI work, use `07-templates/ai-agent-brief.md`.  
- Never commit secrets. Use gitignored `.env` for credentials.  
- Never invent facts about the operator’s companies, people, pricing, or commitments.  
- Do not copy private knowledge into public docs, issues, or Network feeds.  
- Public-safe content must be explicitly labeled and reviewed by the human before external use.

## Editing standards

- Focused changes that improve daily use.  
- Avoid overbuilding tooling unless it removes repeated friction.  
- Update `README.md` when top-level structure or workflow changes.  
- Update `99-meta/changelog.md` for meaningful system changes.  
- Keep templates reusable; put instance data in command center / projects / knowledge.

## Completion handoff

When finishing a task, report:

```text
STATE: DONE | NEEDS HUMAN | BLOCKED
RESULT: What changed or was learned
HUMAN ACTION: None, or the single decision/review needed
EVIDENCE: Files changed, checks run
NEXT: The next useful action, if any
```

## Related systems

- Adoption tracking: https://app.headlessempire.com  
- Network protocol (public signals): https://github.com/HeadlessEmpire/headless-empire-network  
- Product overview: https://headlessempire.com  
