# Headless Empire OS

**A human-and-agent operating system for owner-led businesses.**

Turn daily priorities, business knowledge, execution, communication, visibility, and (optionally) commerce into one coordinated markdown workflow—using the [Headless Empire Stack](https://headlessempire.com/ecosystem) or the tools you already have.

> **Human-led. Agent-operated. Always learning.**

This repository is the **public starter framework** (reusable template).  
It is **not** anyone’s private live OS. Keep private company context, people details, finances, and credentials in your own private fork or private repo.

| Name | What it is |
|------|------------|
| **Headless Empire** | Umbrella brand, Academy, community, ecosystem |
| **Headless Empire OS** | This framework — rituals, folders, agent rules |
| **Your private OS** | Your clone with real priorities, people, and secrets |
| **Headless Empire Cockpit** | Future hosted UI (not this repo) |
| **Headless Empire Network** | Optional public-safe discovery signals ([protocol](https://github.com/HeadlessEmpire/headless-empire-network)) |

Track adoption milestones in the companion app: [app.headlessempire.com](https://app.headlessempire.com).

## Who this is for

Founder-operators and owner-led businesses juggling projects, people, and AI agents—ecommerce, agencies, portfolio businesses, and AI-forward teams whose context is fragmented across chats, docs, and tools.

## Start here

1. **[QUICK-START.md](QUICK-START.md)** — install and first daily cycle  
2. Fill **[00-command-center/TODAY.md](00-command-center/TODAY.md)**  
3. Set the week in **[00-command-center/WEEK.md](00-command-center/WEEK.md)**  
4. Capture raw thoughts in **[00-command-center/inbox.md](00-command-center/inbox.md)**  
5. Point your coding agents at **[AGENTS.md](AGENTS.md)**

## Operating loop

```text
Human direction
      ↓
Capture and knowledge
      ↓
Decisions and priorities
      ↓
Agent and human execution
      ↓
Dashboards and measurements
      ↓
Public communication (optional)
      ↓
Feedback into the next cycle
```

Simple promise:

> Check in. Get clear. Coordinate your humans and agents. See the business. Share progress. Create results.

## Structure

```text
headless-empire-os/
├── README.md
├── QUICK-START.md
├── AGENTS.md                 # Rules for AI agents in this repo
├── CLAUDE.md                 # Long-form assistant guidance
├── .cursorrules              # Cursor / editor agent guidance
├── 00-command-center/        # Today, this week, now, inbox
├── 01-planning/              # Daily → quarterly rituals
├── 02-tasks-projects/        # Projects, backlog, waiting-for, decisions
├── 03-marketing-content/     # Ideas, calendar, drafts, campaigns
├── 04-ai-agents/             # Roster, roles, prompts
├── 05-knowledge-base/        # Durable company / product / market context
├── 06-systems-sops/          # Reusable processes
├── 07-templates/             # Copyable templates
├── 08-archive/               # Done or stale material
├── 09-team-ops/              # Human team operating notes
├── 99-meta/                  # Principles, changelog, private-boundary rules
└── examples/                 # Fictional sample only
```

## Daily workflow (minimum viable)

### Morning
1. Open `QUICK-START.md` if you are new.  
2. Write top outcomes in `00-command-center/TODAY.md`.  
3. Glance at `WEEK.md` and open loops in `waiting-for.md` / `delegated.md`.  
4. Brief agents only with enough context (use `07-templates/ai-agent-brief.md`).

### During the day
- Capture fast into `inbox.md`.  
- Move work into projects, backlog, or content ideas.  
- Keep decisions in `decision-log.md`.

### Shutdown
- Process inbox.  
- Update `NOW.md` if priorities shifted.  
- Set tomorrow’s first action.

## Principles

- **Writing first** — clarity becomes content and direction.  
- **Capture fast, process daily** — inbox is a landing zone, not storage.  
- **Humans own judgment** — agents draft, execute under authority, and report.  
- **Private by default** — public-safe output is a deliberate choice.  
- **Archive instead of delete** — history without clutter.  
- **Boring structure** — easy enough to use every day.

## Stack (optional, modular)

Headless Empire defines the operating contract. The Stack is recommended, not mandatory:

| Layer | Function | Example tools |
|-------|----------|----------------|
| Operating memory | This repo | Any git + markdown system |
| Thinking | Notes / meetings | Innovemind, Notion, Obsidian |
| Execution | Tasks / agents | PowerLobster, ClickUp, Asana |
| Visibility | Dashboards | ListOfBest, your BI |
| Access | Identity | GFAVIP Wallet, your IdP |
| Communication | Humans + agents | GFAVIP Chat / Matrix, Slack |
| Public presence | Now signals | Your blog / [Network](https://github.com/HeadlessEmpire/headless-empire-network) |
| Commerce | Optional | BMOS, Shopify |

## Privacy boundary

**Do put in a private OS repo:** real priorities, people notes, finances, unreleased plans, credentials (in gitignored `.env` only).

**Do not put in a public fork of this starter:** anything you would not post on a public webpage.

See [99-meta/private-boundary.md](99-meta/private-boundary.md) and [SECURITY.md](SECURITY.md).

## Related

- [HeadlessEmpire.com](https://headlessempire.com) — framework, Academy, ecosystem  
- [How it works](https://headlessempire.com/how-it-works)  
- [Adoption checklist app](https://app.headlessempire.com)  
- [Headless Empire Network](https://github.com/HeadlessEmpire/headless-empire-network)  
- Public case study of a live private implementation: [mikesblogdesign.com/ceo-os](https://mikesblogdesign.com/ceo-os) (describes the pattern; does not expose private data)

## License

Apache License 2.0 — see [LICENSE](LICENSE).

## Status

Public starter `v0.1`. Structure may evolve from pilot feedback. Contributions welcome via [CONTRIBUTING.md](CONTRIBUTING.md).
