# OpenClaw Startup 🚀

First-run setup wizard for new OpenClaw agents.

## What it does

1. **Interviews the user** — 8 questions to understand who they are and what the agent should do
2. **Generates tailored files** — SOUL.md, USER.md, IDENTITY.md, AGENTS.md from the interview answers
3. **Scaffolds memory** — daily logs, durable memory, commitments, learnings
4. **Sets up crons** — heartbeat, backup, consolidation, security monitoring (gracefully skips if `openclaw` CLI unavailable)
5. **Hardens security** — injection defense, escalation framework, tool restrictions
6. **Recommends skills** — cognition, agent-memory-loop, battle-tested-agent, and more

## Install

```bash
clawhub install openclaw-startup
```

## Usage

Tell your agent: "Set up my workspace" or "Run the startup wizard"

The agent will walk you through everything interactively.

## Recommended companion skills

- `cognition` — memory architecture
- `agent-memory-loop` — lightweight learning capture
- `battle-tested-agent` — production hardening patterns
- `agent-hardening` — security posture
- `openclaw-backup` — disaster recovery
- `openclaw-guide` — config and troubleshooting

## Philosophy

- Interactive wizard, not a static template dump
- Ask one question at a time
- Show before writing
- Confirm before installing
- The user is in control at every step
- Resume-friendly — detects partial setups and offers to pick up where you left off
