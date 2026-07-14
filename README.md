<p align="center">
  <img src="https://ormus.solutions/mascot/pixellab_liquid_to_braces.gif" alt="Claude Code Skills" width="128" style="image-rendering: pixelated;" />
</p>

<h1 align="center">Claude Code Skills</h1>

<p align="center">
  <em>Reusable skills and frameworks for Claude Code — distilled from real AI-assisted development</em>
</p>

<p align="center">
  <a href="https://github.com/HermeticOrmus/claude-code-skills/stargazers"><img src="https://img.shields.io/github/stars/HermeticOrmus/claude-code-skills?style=flat-square&color=aa8142" alt="Stars" /></a>
  <a href="https://github.com/HermeticOrmus/claude-code-skills/blob/main/LICENSE"><img src="https://img.shields.io/github/license/HermeticOrmus/claude-code-skills?style=flat-square&color=aa8142" alt="License" /></a>
  <a href="https://github.com/HermeticOrmus/claude-code-skills/commits"><img src="https://img.shields.io/github/last-commit/HermeticOrmus/claude-code-skills?style=flat-square&color=aa8142" alt="Last Commit" /></a>
  <img src="https://img.shields.io/badge/Claude_Code-aa8142?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />
</p>

---
Reusable [Claude Code](https://docs.anthropic.com/en/docs/build-with-claude/claude-code) skills extracted from real AI-assisted development sessions.

Every skill here was built to solve a real problem on a real project -- then generalized into a reusable framework. Not theoretical. Battle-tested.

---

## Skills

| Skill | What It Does | Origin |
|-------|-------------|--------|
| [android-apk](./android-apk/) | Build native Android APKs without Android Studio using raw SDK tools (~30KB, <2s builds) | Share-sheet APK for CF Access-protected API (Mar 2026) |
| [calcinate](./calcinate/) | Burn project bloat to reveal essence — intent-anchored, 4 parallel detection agents, tiered plan, gated burn with per-item revert | First test ran on the skills home itself (May 2026) |
| [claude-md-overhaul](./claude-md-overhaul/) | Audit and improve a Claude Code memory layer end-to-end — measure CLAUDE.md and MEMORY.md against Anthropic caps, fill project-portfolio gaps, prune index, install hooks, tier-by-tier with cap-fitting verification | End-to-end memory-layer audit-and-improve session (May 2026) |
| [close](./close/) | End-of-session ritual -- captures state, updates memory, writes summary, exits cleanly | Session lifecycle management (Mar 2026) |
| [google-docs-markdown](./google-docs-markdown/) | Convert markdown to formatted Google Docs with folders, sharing, and logo branding | Event protocol delivery (Feb 2026) |
| [google-drive-operator](./google-drive-operator/) | Analyze, restructure, and manage Google Drive shared folders with full CRUD operations | Client feedback collaboration space (Feb 2026) |
| [handoff](./handoff/) | Write a complete session state capture to HANDOFF.md for cross-session continuity | Session lifecycle management (Mar 2026) |
| [ho](./ho/) | Shorthand alias for /handoff — forwards to the handoff skill | Session lifecycle shorthand (Jul 2026) |
| [meta-prompting-suite](./meta-prompting-suite/) | 9 composable meta-prompting patterns — neutral 4 (prime/distill/goal/agents) + alchemical 5 (Hermetic-voiced prompt/agent/goal/distill/flow). Wrappers over the categorical engine; bridges into built-in /goal and /agents | Daily meta-prompting kit (May 2026) |
| [osint](./osint/) | Multi-wave OSINT research methodology with progressive deepening, source hierarchy, and structured intel output | Intelligence research session (Feb 2026) |
| [pc-ops](./pc-ops/) | Windows system cleanup -- audit programs, services, startup items, processes, and disk usage | OEM laptop system cleanup (Feb 2026) |
| [pickup](./pickup/) | Read a HANDOFF.md and restore session context -- the opposite of /handoff | Session lifecycle management (Mar 2026) |
| [product-feasibility-scout](./product-feasibility-scout/) | Systematic API landscape and feasibility research for product concepts | Parental awareness app research (Feb 2026) |
| [pu](./pu/) | Shorthand alias for /pickup — forwards to the pickup skill | Session lifecycle shorthand (Jul 2026) |
| [ship](./ship/) | Unified shipping pipeline -- scaffold docs, create GitHub repo, push, optional social posting | Open-source publishing workflow (Mar 2026) |
| [site-perf-audit](./site-perf-audit/) | Diagnose and fix performance issues on Next.js / React websites | Medical clinic website optimization (Feb 2026) |
| [unwoke](./unwoke/) | Strip AI theater and ideological bias -- 10 sins, 10 rules, 7-point self-check for truth-seeking responses | Anti-woke AI communication research (Mar 2026) |
| [vibe-engineer](./vibe-engineer/) | The discipline for directing AI codegen -- 5 principles + 5 triggers, applied to Claude's own output too | Google Code Comprehension Interview analysis (May 2026) |
| [vibe-proof](./vibe-proof/) | Security hardening for vibe-coded full-stack apps via parallel multi-agent audit (v2: 85+ issues across 2 projects) | E-commerce + medical platform hardening (Feb 2026) |
| [vercel-inline-cms](./vercel-inline-cms/) | Install a lightweight inline-editing CMS into any Vercel-deployed project — auto-detects framework (Next.js App/Pages Router, Vite + React) and ships a manual-port guide for SvelteKit/Astro/Nuxt/static | Nickson Studios website CMS, generalized for Vercel (May 2026) |

---

## Spotlight: standalone repos

Some skills graduate into their own repos with richer docs and individual install paths. Star them directly:

| Repo | What it does |
|---|---|
| [ormus-handoff](https://github.com/HermeticOrmus/ormus-handoff) | Session state capture — resume tomorrow where you left off, even on a different machine |
| [ormus-pickup](https://github.com/HermeticOrmus/ormus-pickup) | Restore session context at the start of a new session — inverse of /handoff |
| [ormus-absorb](https://github.com/HermeticOrmus/ormus-absorb) | Distill what a session taught you into persistent memory — the learning ritual |
| [ormus-explore](https://github.com/HermeticOrmus/ormus-explore) | Token-optimized AST-based code search (4-8x cheaper than reading full files) |
| [ormus-vibe-proof](https://github.com/HermeticOrmus/ormus-vibe-proof) | Security hardening for vibe-coded full-stack apps — parallel audits + prioritized fixes |
| [ormus-meta-prompting](https://github.com/HermeticOrmus/ormus-meta-prompting) | Categorical foundations for prompt engineering — 100% accuracy on Game of 24 |

These six together form the **ormus session lifecycle** — composable Claude Code skills for serious cross-day, cross-machine work.

---

## How to Use

These are Claude Code skills. To use one:

1. Copy the skill directory to `~/.claude/skills/`
2. Invoke by name in Claude Code (e.g., type the trigger phrase)
3. Or read the SKILL.md and apply the framework manually

Each skill is self-contained with clear instructions, templates, quality criteria, and anti-patterns.

## Structure

```
claude-code-skills/
  README.md              # This catalog
  LICENSE                # MIT + Gold Hat Addendum
  CLAUDE.md              # Repo instructions for Claude Code
  <skill-name>/
    SKILL.md             # The skill
    references/          # Optional supporting files
```

## The Extraction Process

Skills are extracted from real development sessions through a structured process:

1. **Identify** -- What repeatable pattern emerged from this session?
2. **Abstract** -- Separate the reusable structure from the specific context
3. **Generalize** -- Make it work for any project, not just the original one
4. **Validate** -- Does it hold up when applied to a different problem?

The goal: turn one-off problem-solving into permanent capability.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Skills should:

- Emerge from real work (not invented for the repo)
- Include an "Origin" section documenting the source project
- Be self-contained and clearly documented
- Follow the Gold Hat philosophy: empower, never extract

## Philosophy

These skills follow the **Gold Hat** principle: every tool should empower its user, not create dependency. Skills teach a process, not just execute a task. If you're curious about the deeper methodology behind the extraction process, see the [wiki](https://github.com/HermeticOrmus/claude-code-skills/wiki).

## License

MIT + Gold Hat Addendum. See [LICENSE](LICENSE).

---

## Part of the Libre Open-Source Stack for Claude Code

This repository is part of a growing family of open-source toolkits for Claude Code.

### Libre suite — comprehensive plugin bundles

- [LibreUIUX-Claude-Code](https://github.com/HermeticOrmus/LibreUIUX-Claude-Code) — UI/UX development (152 agents, 70 plugins, 76 commands, 74 skills)
- [LibreArch-Claude-Code](https://github.com/HermeticOrmus/LibreArch-Claude-Code) — Software architecture and system design
- [LibreCopy-Claude-Code](https://github.com/HermeticOrmus/LibreCopy-Claude-Code) — Technical writing and documentation engineering
- [LibreDevOps-Claude-Code](https://github.com/HermeticOrmus/LibreDevOps-Claude-Code) — DevOps engineering and infrastructure automation
- [LibreEmbed-Claude-Code](https://github.com/HermeticOrmus/LibreEmbed-Claude-Code) — Embedded systems, firmware, and IoT development
- [LibreFinTech-Claude-Code](https://github.com/HermeticOrmus/LibreFinTech-Claude-Code) — Financial technology development
- [LibreGEO-Claude-Code](https://github.com/HermeticOrmus/LibreGEO-Claude-Code) — AI-search optimization (ChatGPT, Perplexity, Gemini, Google AI Overviews)
- [LibreGameDev-Claude-Code](https://github.com/HermeticOrmus/LibreGameDev-Claude-Code) — Game development across Godot, Unity, Unreal
- [LibreMLOps-Claude-Code](https://github.com/HermeticOrmus/LibreMLOps-Claude-Code) — ML engineering and AI operations
- [LibreMobileDev-Claude-Code](https://github.com/HermeticOrmus/LibreMobileDev-Claude-Code) — Mobile app development (Flutter, React Native, native iOS, native Android)
- [LibreSecOps-Claude-Code](https://github.com/HermeticOrmus/LibreSecOps-Claude-Code) — Security operations

### Skills mini-repos — single CLAUDE.md drop-ins

- [vibe-engineer-skills](https://github.com/HermeticOrmus/vibe-engineer-skills) — Direct AI codegen well (hypothesis → scope → validate → reject working-but-wrong)
- [markdown-discipline-skills](https://github.com/HermeticOrmus/markdown-discipline-skills) — Strip AI-slop from markdown (no em dashes, no marketing fluff)
- [shell-safety-skills](https://github.com/HermeticOrmus/shell-safety-skills) — `set -euo pipefail` discipline + 15 failure-mode examples
- [commit-standard-skills](https://github.com/HermeticOrmus/commit-standard-skills) — Ormus Commit Standard v1.0 + commit-msg hook + commitlint
- [unwoke-skills](https://github.com/HermeticOrmus/unwoke-skills) — Strip AI theater (ten sins to eliminate, symmetric engagement)
- [python-conventions-skills](https://github.com/HermeticOrmus/python-conventions-skills) — Modern Python 3.11+ (types, pathlib, async, ruff, mypy, uv)
- [typescript-conventions-skills](https://github.com/HermeticOrmus/typescript-conventions-skills) — TypeScript strict mode, discriminated unions, Result types
- [hermetic-laws-skills](https://github.com/HermeticOrmus/hermetic-laws-skills) — Seven Hermetic Principles applied to engineering
- [riper-workflow-skills](https://github.com/HermeticOrmus/riper-workflow-skills) — Research / Innovate / Plan / Execute / Review systematic dev
- [six-day-cycle-skills](https://github.com/HermeticOrmus/six-day-cycle-skills) — Sustainable shipping cadence with mandatory rest
- [token-optimization-skills](https://github.com/HermeticOrmus/token-optimization-skills) — Claude Code token + context optimization
- [osint-skills](https://github.com/HermeticOrmus/osint-skills) — OSINT research methodology (multi-wave investigative spiral)
- [calcinate-skills](https://github.com/HermeticOrmus/calcinate-skills) — Stage 1 of the Magnum Opus (burn project bloat)
- [claude-md-overhaul-skills](https://github.com/HermeticOrmus/claude-md-overhaul-skills) — Audit CLAUDE.md and MEMORY.md against caps
- [session-handoff-skills](https://github.com/HermeticOrmus/session-handoff-skills) — Session handoff + pickup discipline
- [naming-skills](https://github.com/HermeticOrmus/naming-skills) — Product naming methodology (mine the brand's vocabulary)
- [magnum-opus-skills](https://github.com/HermeticOrmus/magnum-opus-skills) — Seven-stage alchemy applied to project transformation

### Template source

- [andrej-karpathy-skills](https://github.com/HermeticOrmus/andrej-karpathy-skills) — the canonical single-file CLAUDE.md pattern (fork of jiayuan_jy's original)

Star the family, not just one — that's how the suite stays coherent.
