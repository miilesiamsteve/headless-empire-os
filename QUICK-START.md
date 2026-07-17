# Quick start — first complete daily cycle

Goal: in under an hour, go from empty clone to **one real daily check-in** with clear human and agent next actions.

## 1. Install

```bash
# Prefer a *private* copy for real work
gh repo create your-org/my-headless-empire-os --private --template HeadlessEmpire/headless-empire-os
# or:
git clone https://github.com/HeadlessEmpire/headless-empire-os.git my-headless-empire-os
cd my-headless-empire-os
# If you cloned the public template for real use, make the remote private or fork private.
```

Open the folder in your editor (Cursor, VS Code, etc.). Agents should read `AGENTS.md` first.

## 2. Configure once

| Step | Action |
|------|--------|
| Identity | Replace `Operator` placeholders with your name in command-center files |
| Business | Add a short company one-pager under `05-knowledge-base/company/` |
| Tools | Note your stack in `05-knowledge-base/company/tool-stack.md` |
| Agents | List agents in `04-ai-agents/agent-roster.md` |
| Secrets | Copy `.env.example` → `.env` (gitignored). Never commit secrets |
| Adoption | Sign in at [app.headlessempire.com](https://app.headlessempire.com) and mark “Clone & configure” complete |

## 3. Morning check-in (15–20 min)

Open [00-command-center/TODAY.md](00-command-center/TODAY.md) and answer:

1. **What happened yesterday?** (wins, shipped, blocked)  
2. **What matters today?** (Top 3 outcomes, not a long task dump)  
3. **What should humans do?**  
4. **What should agents do?** (use [07-templates/ai-agent-brief.md](07-templates/ai-agent-brief.md))  
5. **What should stay internal?**  
6. **What (if anything) is public-safe to share later?**  

Then glance at:

- [WEEK.md](00-command-center/WEEK.md) — Big 3 for the week  
- [waiting-for.md](02-tasks-projects/waiting-for.md) — open loops  
- [delegated.md](02-tasks-projects/delegated.md) — work others own  

## 4. Capture and process

All day: dump into [inbox.md](00-command-center/inbox.md).  
Once daily: move items to project, backlog, content ideas, or archive.

## 5. Shutdown (5–10 min)

- Process inbox  
- Log any real decision in [decision-log.md](02-tasks-projects/decision-log.md)  
- Update [NOW.md](00-command-center/NOW.md) if the picture changed  
- Write **tomorrow’s first action** at the bottom of TODAY.md  

## 6. First weekly cycle (end of week)

Use [01-planning/weekly/README.md](01-planning/weekly/README.md) and a copy of [07-templates/weekly-plan.md](07-templates/weekly-plan.md):

- Big 3 outcomes for next week  
- Content / marketing commitments  
- Delegation and waiting-for review  
- One lesson that improves the OS  

## Done when

- [ ] TODAY.md filled for a real day  
- [ ] Inbox processed at least once  
- [ ] One agent brief written (even if simple)  
- [ ] You know where projects, decisions, and knowledge live  
- [ ] Adoption app checklist updated  

## Common mistakes

| Mistake | Fix |
|---------|-----|
| Putting real secrets in markdown | Use gitignored `.env` only |
| Publishing this repo with private data | Use a **private** repo for your live OS |
| Overbuilding folders before day 1 | Run one daily cycle first |
| Treating agents as owners | Humans approve commitments and external messages |
| Maintaining a second “real” task system without linking | Pick a source of truth; link out from projects |

## Next

- Read [99-meta/operating-principles.md](99-meta/operating-principles.md)  
- Optional: publish a public-safe Now update (see Network protocol)  
- Optional: connect Stack apps (Innovemind, PowerLobster, ListOfBest, GFAVIP)  
