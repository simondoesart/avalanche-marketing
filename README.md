# Avalanche Marketing Plugin

A one-stop shop for the Avalanche marketing team, trained on Avalanche documentation, the marketing messaging framework, tone of voice, and the June 2026 visual guidelines. Everything runs through the lens of **Avalanche is Built for Business** — appealing to institutions, banks, enterprises, and fintechs.

## Install

- **Recommended (internal):** install the distributed `avalanche-marketing.plugin` file — it includes the private brand files.
- From this repo: clone and install the folder as a plugin. Note that private files (`*PRIVATE*`) are **not** in the repo; ask the brand team for them and drop them into `brand/`.

**Auto-start:** a SessionStart hook makes Claude open each new session with the `/avalanche-start` welcome menu automatically (or, if you lead with a specific request, it handles that and reminds you the menu exists). You can also type `/avalanche-start` anytime.

**Messaging accuracy:** the full messaging framework is baked into the plugin as a local file (`brand/messaging-framework-PRIVATE.md`) — Claude reads it directly, so no Google access or public doc is required at runtime. It's a snapshot: when the source Google Doc changes, refresh the file and re-package.

## Commands

| Command | Purpose |
|---|---|
| `/avalanche-start` | Welcome summary + command list |
| `/competitive-audit` | Audit competitor marketing & paid work (Solana, Ethereum, Ripple/XRP, Canton, Sui, …) |
| `/social-audit` | Audit competitor social accounts |
| `/avalanche-social-audit` | Audit our own @avax social presence |
| `/trends-audit` | Current trends + forecast from events, holidays, industry calendar |
| `/tone-of-voice` | Tone rules; review/rewrite copy on-brand |
| `/copywriting` | Evergreen copy bank + new on-brand copy |
| `/creative-assets` | Links to logos, endcards, templates, color chart |
| `/campaign-strategy` | Full campaign briefs |
| `/social-strategy` | Channel plans and content pillars |
| `/creative-strategy` | Concepts, storytelling, PR hooks, script ideas, what to avoid |

## Brand knowledge (in `brand/`)

- `visual-guidelines.md` — distilled June 2026 brand guidelines (colors, type, imagery, layout)
- `assets/avalanche-color-chart.png` — brand color chart
- `avalanche-knowledge.md` — tech + ecosystem facts for marketers, with live-docs lookup instructions (`build.avax.network/...page.md` returns raw markdown; index at `/llms.txt`)
- `copy-bank.md` — evergreen lines, formulas, avoid-list
- `resource-links.md` — public links
- `messaging-framework-PRIVATE.md`, `resource-links-PRIVATE.md` — internal only (see below)

## Privacy model

This repo is **private** (team-only access), so the internal brand files (`*PRIVATE*` — messaging framework, internal links) are tracked and included in marketplace installs.

- **Never make this repo public** without first re-adding `**/*PRIVATE*` to `.gitignore`, removing the private files, and purging git history (they'd remain in old commits).
- The `.plugin` package also contains the private files — internal distribution only.
- Keep the `PRIVATE` suffix on new internal files so they're easy to find and protect if visibility ever changes.

## Google integration

The team uses company OAuth, so the plugin doesn't hardcode a Google connection. Each marketer can connect their own Google account: **Settings → Connectors → Google Drive** (works with a personal account). When connected, skills offer deliverables as Google Docs; otherwise they save local files. Internal Google links in `resource-links-PRIVATE.md` still require your normal company access.

## Companion plugins that pair well

- `avalanche-video` — full branded video pipeline (`/make-video`)
- `marketing` suite — brand-review, campaign-plan, seo-audit, email-sequence
- `brand-voice` — deep voice enforcement for high-stakes content
- `sales:competitive-intelligence` — interactive battlecards

## Updating the plugin

Brand facts age. When guidelines or messaging change: update the files in `brand/`, bump `version` in `.claude-plugin/plugin.json`, re-zip as `.plugin` for internal distribution, and push public-safe changes to the repo.
