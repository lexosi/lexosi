# Hey, I'm Lex

**I direct live products with people inside them, and I build the systems that keep them under control.** Ten years of live game productions, communities and studios (2016-2026); since January 2024, multi-agent LLM systems, the first one in production for an external client under NDA; open source and built in public since 2026.

Live, at scale, no second takes: **3,000-4,000 concurrent players** on the production servers behind the live series and events I directed (2016-2025) and **65,000 concurrent players** on a Fortnite island I led (2024).

---

### What I'm building (public, verified 2026-11-09: they build and their tests pass)

- **[loopward](https://github.com/lexosi/loopward)** — reliability layer for multi-agent LLM systems: class-jump anti-loop, human stop-gates, per-run audit trail. 203 tests, offline demo, CI that installs from git on a clean runner, written threat model.
- **[UniversalCode](https://github.com/lexosi/UniversalCode)** — Windows TUI with embedded elevated shells and a token-based loopback privilege bridge. Hexagonal architecture, 172 tests, `mypy --strict` clean across 53 modules, documented security model.
- **[claude-informes](https://github.com/lexosi/claude-informes)** — Claude Code `Stop` hook that saves every turn's answer as JSON at zero token cost. 360 tests, CI on Python 3.10-3.14.
- **[ai-code-reviewer](https://github.com/lexosi/ai-code-reviewer)** — Rust binary run by a git post-commit hook: diff → Claude → Telegram. `unwrap()` forbidden outside tests, `clippy -D warnings` clean, 30 tests.
- **[uefn-mcp-server](https://github.com/lexosi/uefn-mcp-server)** — MCP server to drive UEFN from Claude Code, extended and hardened: editor-log fix, deprecated-API migration, viewport screenshots, 22 tests with negative controls, CI, 3 ADRs. Upstream PR open since Jun-2026 (unreviewed).
- **[multiagent-system-lex](https://github.com/lexosi/multiagent-system-lex)** — architecture reference (sanitized, not installable by design) of my private 19-agent system: 17 of the 19 agent definitions, deny-by-default hooks and the measured findings.

Private, demo on request: the full 19-agent system (13 Claude + 6 DeepSeek), `agentic-os` (personal agent OS with independent auditors and a decision vault), and a heavily extended fork of career-ops.

### What I shipped before code

- **ONLYUP FALL GUYS** (Mist Creative, Aug 2024) — #1 most-played island across all of Fortnite for several hours, #1 in its category for two weeks, 65K concurrent peak. Promoted by the official Fortnite account: [x.com/Fortnite/status/1821969776148730147](https://x.com/Fortnite/status/1821969776148730147).
- **Pedigree ft. Minecraft** (with Rift Agency, Nov 2024) — brand activation: concept, server, mini-games, security, Discord. [Rift Agency](https://x.com/rift_agency/status/1873816878910759280).
- **Frank Cuesta's Sanctuary map** (Jan 2025) — [Javi Oliveira](https://x.com/javioliveira/status/1880604120274682190).
- **Tomatecraft** — my own Minecraft network: 5 on payroll, 40+ collaborators, Java/mobile crossplay before almost anyone.
- 10+ commissioned live series and events for the biggest Spanish-speaking creators (Rubius, Vegetta777, Willyrex, Alexby11, xFarganx, Los Noobs), 2016-2025. YouTube channel: 577K subscribers.

### Write-ups

- **[What Advisory Rules Actually Do in an Agent Loop](https://dev.to/lexosi/what-advisory-rules-actually-do-in-an-agent-loop-bke)** — advisory rules produced 0/3 compliance right after canonization; deny-by-default hooks replaced them. The numbers, with the evidence class labeled.
- **[Ten years directing live products before I knew it was called product management](https://dev.to/lexosi)** — the product track record behind the gaming work.
- **[A Line of Documentation Was Acting as a Global Config Flag](https://dev.to/lexosi/a-line-of-documentation-was-acting-as-a-global-config-flag-3635)** — prose and constants in an agent system are the control plane.

---

### How I work

- **Enforcement over trust** — I deny the bad path at the hook level; I don't ask the model nicely.
- **Probe before fix** — cheap A/B tests to isolate root cause before touching code.
- **I say what I did not do** — every figure at the precision I can defend; private work labeled private.

### Stack

`Python` · `Rust` · `Java` (certified) · `TypeScript/Node` · `Verse (UEFN)` · multi-agent orchestration (Claude Code) · MCP · SQL/NoSQL

### Languages

Catalan (native) · Spanish (native) · French (native) · English (professional)

### Connect

[lexosi.com](https://lexosi.com) · [LinkedIn](https://linkedin.com/in/lexlexosi) · [X](https://x.com/lexosi_) · [dev.to](https://dev.to/lexosi) · iamlexosi@gmail.com

**Judge me by the code — and by the players.**
