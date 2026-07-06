---
name: avalanche-start
description: Show the Avalanche marketing plugin welcome summary and list of available commands. Use when the user says "/avalanche-start", "start", "help", "what can this plugin do", "show commands", or at the beginning of a session when a marketer asks what's available.
---

# Avalanche Marketing — Start

Present a concise welcome and the command menu. Do not run any other skill until the user picks one.

First, silently read `../../brand/messaging-framework-PRIVATE.md` (relative to this skill's base directory) if it exists, so brand context is loaded for the session. If it's missing, use `../../brand/copy-bank.md` and `../../brand/visual-guidelines.md`.

Then display:

**Avalanche Marketing Hub — Technology Built for Business.** A one-stop shop trained on Avalanche docs, messaging, tone of voice, and visual guidelines.

| Command | What it does |
|---|---|
| `/competitive-audit` | Audit competitor marketing & paid campaigns (Solana, Ethereum, Ripple/XRP, Canton, Sui, or any list) |
| `/social-audit` | Audit competitor social accounts — recent posts, media, what's working/not |
| `/avalanche-social-audit` | Audit our own @avax presence — wins, misses, recommendations |
| `/trends-audit` | Current + forecast trends from news, culture, holidays, crypto/finance calendar |
| `/tone-of-voice` | Pull up tone-of-voice rules and apply them to any draft |
| `/copywriting` | Evergreen copy bank — headlines, taglines, CTAs, do/don't language |
| `/creative-assets` | Links to logos, endcards, templates, color chart, brand folders |
| `/campaign-strategy` | Full campaign brief: objectives, audience, channels, calendar, KPIs |
| `/social-strategy` | Channel-level social strategy and content pillars |
| `/creative-strategy` | Concepts, storytelling angles, PR hooks, script ideas, what to avoid |

Also mention:

- Video work: if the `avalanche-video` plugin is installed, `/make-video` runs the full branded video pipeline.
- Docs lookup: any build.avax.network page + `.md` returns raw markdown; index at build.avax.network/llms.txt — used automatically for accurate technical claims.
- Google Docs output: if their Google Drive connector is connected (Settings → Connectors → Google Drive, personal OAuth), deliverables can be created as Google Docs; otherwise files are saved locally.

Close by asking what they're working on today.
