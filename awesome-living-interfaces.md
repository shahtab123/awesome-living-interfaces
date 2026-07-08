# Awesome Living Interfaces

A curated, **verified** database of "living software" — tools that visualize AI agents, systems, or activity as characters, worlds, or arenas instead of logs and dashboards.

> Research method: every entry below was checked against GitHub, Product Hunt, Hacker News, Reddit, X, or the project's own site. Names that could not be independently verified (from an earlier, unverified pass) were dropped rather than repeated. See "Rejected / Unverified" at the bottom.

---

## Category A: AI-Agent Pixel Offices
**By far the most saturated category.** Nearly all descend from one project — Pixel Agents by Pablo De Lucca, posted to r/ClaudeCode in Feb 2026 — which spawned 15+ forks/clones within months. The pattern: your coding agent (Claude Code, Codex, Gemini CLI, Cursor...) becomes a pixel-art character that walks, sits, types, and raises a speech bubble when it needs approval.

| Project | Description | Link | Status |
|---|---|---|---|
| **Pixel Agents** | The original. VS Code ext + standalone CLI, agents as sprites, office editor, 64×64 grid | github.com/pablodelucca/pixel-agents | Open source |
| **Pixel Office (JetBrains)** | IntelliJ port — 80+ furniture items, alien/cat/zoo themes | plugins.jetbrains.com/plugin/31298 | Open source |
| **pixel-agents-gemini / -codex / -cursor** | Same concept wired to Gemini CLI, Codex, Cursor | github.com/hyungseokyoon, MichaelMa907, ananasDDA | Open source |
| **AgentOffice** | Self-growing office — agents hire interns, Phaser+React, Ollama-powered, capped at 7 agents | github.com/harishkotra/agent-office | Open source |
| **agents-in-the-office** | Tauri app; NPCs mirror real Claude Code/Gemini CLI actions; subagent badges; sound packs; i18n | github.com/gukosowa/agents-in-the-office | Open source |
| **Claude Office Visualizer** | Multi-floor building, "Command Center" cross-session view, 12-mode whiteboard (kanban/org chart/heat map/news ticker/etc.) | github.com/paulrobello/claude-office | Open source |
| **aphae** | Godot 4 — full life-sim: relationships, aging, death, RimWorld-style "Drama Director" | github.com/rsanandres/aphae | Open source |
| **agent-office** (Pixel-Process-UG) | Telegram bot control, Slack/GitHub/Linear integrations, office-hours config, team voting | github.com/fwartner/clawd-office | Open source |
| **pixtuoid** | Terminal-native, Rust, half-block pixel art, works across 9+ agent CLIs, a cat/dog roams the office | github.com/IvanWng97/pixtuoid | Open source |
| **pixel-office-openclaw** | Auto-detects local OpenClaw instances, Express + Canvas | github.com/neomatrix25/pixel-office-openclaw | Open source |
| **Agent Town** | Built on OpenClaw — walk the office as "the boss," town map + marketplace, cloud version planned | github.com/geezerrrr/agent-town | Open source |
| **Star-Office-UI** | HTML/JS office, daily notes, "guest agents" dropping by | github.com/ringhyacinth/Star-Office-UI | Open source (art assets non-commercial) |
| **Bit Office** | Leader model + planning/coding/review rooms, 12 selectable themes | producthunt.com/products/github-311 | Open source |
| **Agent Pixels** | Paperclip plugin, "security cam" framing, multiple camera views | agent-pixels.com | Free plugin |
| **Moltcraft** | Isometric world for Moltbot — buildings = cron jobs/tokens/skills, voice chat, runs on a Raspberry Pi | github.com/askmojo/moltcraft | Open source |
| **Outworked** | Electron/Mac app, agents as "employees," git panel, cost dashboard, original 8-bit soundtrack | github.com/outworked/outworked | Open source (GPL-3.0) |
| **pixel-agent-desk** | Electron; GitHub-style activity heatmap; token cost analytics | github.com/Mgpixelart/pixel-agent-desk | Open source |
| **Thinkroid Space** | Explicit "agents living in a world you define," roadmap toward a cross-space "Grid" | thinkroid.com | Open source components |
| **TaskVille** | Gamified virtual office, scheduled/autonomous task pickup | taskville.co | Commercial |
| **opencode-pixel-office** | Same concept for OpenCode + Claude Code simultaneously, mobile companion via QR | ddx-510.github.io/opencode-pixel-office | Open source |

**Notable discourse:** a widely-shared critique (*"This Viral AI Tool Does Nothing, But Developers Can't Stop Watching It"*) argues this entire genre is popular *because* it's decorative rather than functional — it visualizes agents without giving any control over them, and reads as anxiety-soothing theater more than real UX progress. Worth keeping in mind as you build this out.

---

## Category B: AI Trading Arenas
**Not spatial at all — the "world" here is the market itself.** These are leaderboard-driven, spectator-sport framings of AI models trading real money, covered heavily on X/crypto media.

| Project | Description | Link | Status |
|---|---|---|---|
| **Alpha Arena** (Nof1.ai) | The flagship. Frontier LLMs (GPT-5, Claude, Gemini, Grok, DeepSeek, Qwen) each trade $10k real capital live on Hyperliquid; fully on-chain, public leaderboard; raised $15M from Sui Group + Karatage | nof1.ai | Live, funded |
| **Rallies.ai — AI Trading Arena** | Same concept applied to US equities/indices | rallies.ai | Live |
| **Agent Arena** (Arbitrum) | On-chain competition between crypto-native AI trading agent teams, $10k each, fully observable on-chain | blog.arbitrum.io/agent-arena | Live |
| **BingX AI Arena** | Exchange-run version, live AI models trading perps side by side, one-click copy trading | bingx.com | Commercial |
| **AI Arena** | Different vertical: NFT fighters trained by humans, battle autonomously, earn $NRN — "train/fight/earn" framing but combat, not markets | aiarena (playtoearn.com) | Live, Web3 |
| **IMMT** | Crypto trading + AI advisor platform with a "MetaWorld" where users craft AI characters — closest to a visual trading-world concept, but primarily a DeFi/AI-agent product | immt.io | Commercial |

---

## Checked, but not a fit for this list

| Category | What I found | Why it's excluded |
|---|---|---|
| DevOps / "Kubernetes village" | Only literal IoT digital-twin tools (Azure Digital Twins Explorer, Databricks digital twin, NVIDIA Omniverse) | Real 3D/IoT modeling tools, not gamified pixel-world dashboards |
| Cybersecurity SOC-as-castle | Nothing found | Aspirational category, no populated examples yet |
| CRM-as-houses, Logistics-warehouse | Only generic gamified-CRM SaaS (leaderboards/badges) and standard kanban tools | Gamification ≠ "living world" — no spatial/character metaphor |

---

## Rejected / Unverified (from an earlier research pass — do not reuse)
Claw3D, BagIdea Office, PixelDesk, KozyAgent, and "AI Agent Visualization" (gridchins.ru) never turned up in GitHub, Product Hunt, Hacker News, X, or general web search across multiple query attempts. Treat as possibly fabricated rather than re-include them.

---

## Suggested schema for the full database
```
Project | Demo | GitHub | Video | Screenshots | Art style (Pixel/Isometric/3D) |
Domain (AI-Office/Trading/DevOps/etc.) | Interaction (Passive/Interactive/Autonomous/Competitive-Spectator) |
Tech stack | Status (Open Source/Commercial/Prototype)
```
