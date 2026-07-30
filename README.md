# Max Sutton

Senior SDET at the NBA. I build AI agent systems — at work and in the open.

I build the QA department's AI tooling: a test-triage agent on Claude Opus (Bedrock) that
diagnoses CI failures with reported confidence and updates its own review skills as new failure
patterns emerge, plus AI workflows for test creation, code review, and TypeScript/Playwright
migrations. Before that: eight years of test automation and performance engineering across
Chipotle, Groundswell, AppOnboard, and Tapcart.

After hours I run local-first agents on my own hardware and build the infrastructure they need to
be trusted:

- **[Homunculus](https://github.com/maxwellcsutton/Homunculus)** — a local-native autonomous agent
  runtime: heartbeat scheduler, multi-lane llama.cpp inference, tiered self-curated memory, and a
  warm-KV prompt-caching scheme that saves ~12–14K tokens of prefill per turn.
- **[Idle-Tower](https://github.com/maxwellcsutton/Idle-Tower)** — an open-source, deterministic
  idle game where a local LLM drives Player 1 over an HTTP tool-calling contract. Fork it and
  design your own.
- **[devenv-boilerplate-for-claude-code](https://github.com/maxwellcsutton/devenv-boilerplate-for-claude-code)**
  — a Claude Code starter kit for safe agentic development: full-handoff CLAUDE.md, doc-drift
  hooks, skill discipline, and guardrails for unattended runs.
- **[agent-validation-harness](https://github.com/maxwellcsutton/agent-validation-harness)** — an
  LLM-as-judge pipeline for empirical changes: premise-verification agents, blind cross-family
  judges, a 2-of-2 landing rule, and hooks that hard-limit autonomous runs.
  Uncomment when the repo lands (use final name):
- **[multi-agent-hub](https://github.com/maxwellcsutton/multi-agent-hub)** — a self-hosted,
  private-mesh web console for launching and piloting headless Claude/Kimi/Qwen CLI sessions
  against any local repo, from any device.
- **[3d-printer-pi](https://github.com/maxwellcsutton/3d-printer-pi)** — cloud dashboard and print
  queue for my BIQU B1, with Discord-gated job handoffs between prints.

The thread through all of it: agents are only useful if you can trust their output. Judges should be blind, reviewers should be a different model family than the
author, and autonomous runs get hard budgets.

**Elsewhere:** [maxsutton.dev](https://maxsutton.dev) ·
[LinkedIn](https://www.linkedin.com/in/maxwell-sutton-21664337)
