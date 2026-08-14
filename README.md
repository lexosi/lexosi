# Hey, I'm Lex

**I design and ship AI-native systems.** I build multi-agent orchestration with real enforcement, audit trails, and reliability layers — and I build it in public.

Before code, I led technical delivery on live game events at scale: **3K+ and 65K+ concurrent players** in production, real-time, no second takes.

---

### What I'm building

- **[multiagent-system-lex](https://github.com/lexosi/multiagent-system-lex)** — a 19-agent orchestrator designed from scratch. Hook-level enforcement (hard-block, not soft rules), anti-loop discipline (3 attempts → class-jump), and a full audit trail across 171 documented runs. This is the system I dogfood daily.
- **[loopward](https://github.com/lexosi/loopward)** — the reusable reliability layer extracted from that work: anti-loop and enforcement primitives for LLM-driven workflows.
- **[uefn-mcp-server](https://github.com/lexosi/uefn-mcp-server)** — an MCP server I extended and hardened: CI matrix (3.11/3.12), split test architecture, architecture decision records, upstream PR (pending review).

> The arc: extend others' tools → design my own system → extract the reusable layer. Iteration, not abandonment.

### Write-ups

- **[What Advisory Rules Actually Do in an Agent Loop](https://dev.to/lexosi/what-advisory-rules-actually-do-in-an-agent-loop-bke)** — advisory rules produced 0/3 compliance right after canonization; deny-by-default hooks replaced them. The numbers, with the evidence class labeled.
- **[A Line of Documentation Was Acting as a Global Config Flag](https://dev.to/lexosi/a-line-of-documentation-was-acting-as-a-global-config-flag-3635)** — prose and constants in an agent system are not documentation about the control plane; they are the control plane.

---

### How I work

- **Enforcement over trust** — I deny the bad path at the hook level, I don't ask the model nicely.
- **Probe before fix** — cheap A/B tests to isolate root cause before touching code. Empirical, not guesswork.
- **Design before I type** — brief and decision records first, implementation second.

---

### Stack

`Rust` · `Python` · `Java` · multi-agent orchestration (Claude Code) · MCP · AI-native systems end-to-end

---

### Languages

🇪🇸 Spanish (native) · 🇫🇷 French (fluent) · English (professional)

---

### Connect

[LinkedIn](https://linkedin.com/in/lexlexosi) · [X](https://x.com/lexosi_) · iamlexosi@gmail.com

**Judge me by the code.**
