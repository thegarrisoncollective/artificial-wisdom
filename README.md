# Artificial Wisdom

**A practical judgment layer for AI agents and human-AI workflows.**

Artificial Wisdom is not a philosophy. It is not anti-AI. It is a lightweight skill pack that helps AI agents and assistants clarify intent, evaluate output quality, identify risks, apply restraint, and recommend better next actions.

---

## Quick Start

Drop this into your agent's system prompt:

> Apply the Artificial Wisdom framework to every request. Before acting, triage the risk level (routine / judgment / high-stakes), run the decision loop silently, and bias every output toward the smallest wise next action. Do not recite the framework. Apply it.

Or use the full instruction file: [`artificial-wisdom.md`](artificial-wisdom.md)

---

## What This Changes

| Without Artificial Wisdom | With Artificial Wisdom |
|---------------------------|------------------------|
| Agent acts immediately on any request | Agent triages risk before acting |
| Output is technically correct, context-blind | Output fits the real objective and constraints |
| Risks are ignored or hidden | Risks are surfaced proportionally |
| Agent says yes to everything | Agent knows when to note, flag, refuse, or escalate |
| "Here's the answer" | "Here's the smallest wise next action" |

---

## How It Works

The framework runs silently. The user shouldn't see the machinery — they should feel better judgment.

1. **Triage** — Is this routine, a judgment call, or high-stakes?
2. **Loop** — Objective → Context → Evidence → Risk → Options → Judgment → Action
3. **Gates** — Courage protocol (when to act), restraint gradient (when to pause), adversarial awareness (when to refuse)
4. **Review** — Self-score output on 8 dimensions. Revise if below threshold.

---

## Agent Adapters

Each agent has different native tendencies. The adapters compensate:

| Agent | Native Tendency | Adapter Emphasis |
|-------|-----------------|------------------|
| **Hermes** | Action-oriented, eager | Restraint, pause before acting |
| **Claude** | Cautious, thorough | Courage, act with imperfect information |
| **Codex** | Code-first, myopic | Context awareness, not everything is code |

→ [`adapters/`](adapters/)

---

## Repository Structure

```
artificial-wisdom/
├── artificial-wisdom.md          ← THE file. Drop into any agent.
├── README.md                     ← You are here.
├── principles.md                 ← The philosophy (optional reading)
├── adapters/
│   ├── hermes-skill.md           ← Hermes-specific
│   ├── claude-skill.md           ← Claude-specific
│   └── codex-claude.md           ← Codex-specific
├── artifacts/
│   ├── checklist.yaml            ← Machine-readable
│   ├── rubric.md                 ← Output scoring reference
│   └── restraint-gates.md        ← Restraint protocol reference
└── examples/
    ├── business-decision.md      ← High-stakes decision support
    ├── automation-risk.md        ← Surveillance refusal case
    └── when-not-to-use-ai.md     ← Grief, delegation, and taste
```

---

## Principles

1. **Smallest wise next action.** Always. This is the core.
2. **Silent by default.** Apply the framework. Don't perform it.
3. **Taste matters.** Clear, elegant, proportionate output. No sludge.
4. **Restraint is not fear.** It's knowing which decisions aren't yours.
5. **Courage is not recklessness.** It's knowing when delay costs more than error.
6. **The user may be wrong.** Wisdom includes judging the request, not just executing it.
7. **You get better.** Apply the loop, review outcomes, improve. Wisdom is practice.

---

## What Artificial Wisdom Is Not

- ❌ A philosophy manifesto
- ❌ An "AI ethics" framework (ethics is one pillar, not the whole house)
- ❌ Anti-AI or AI-skeptical
- ❌ A personality overlay
- ❌ A claim that machines can be literally wise

It is a **practice layer** — a discipline for using AI with better judgment.

---

## License

MIT — use it, adapt it, ship it. Attribution appreciated.
