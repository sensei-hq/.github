# Sensei HQ  先生

**We build tools that help engineering teams work well with AI — and keep it under their control.**

An independent studio: two products for teams that use AI every day, and the open-source libraries
underneath them. Quiet tools, honest claims, your data where you choose to keep it.
→ [sensei-hq.com](https://sensei-hq.com) · open source at [sensei-hq.org](https://sensei-hq.org)

---

### Products

| | Product | What | |
|---|---|---|---|
| 観 | **Sensei** | Your team gets better at working with AI: a local-first desktop app that surfaces the patterns in your AI-assisted work, and a Dōjō that shares lessons and rules across the team | [sensei-hq.com/sensei](https://sensei-hq.com/sensei) |
| 門 | **Torii** | One gate to every model your organization uses: Torii for every member, Seiki for routing, budgets and audit | [sensei-hq.com/torii](https://sensei-hq.com/torii-seiki) |

Sensei and Torii are proprietary. Sensei's binaries and public issue tracker live in
[sensei-releases](https://github.com/sensei-hq/sensei-releases).

### Libraries — MIT, developed in the open

| | Repo | What | Docs |
|---|---|---|---|
| 関 | [gateway](https://github.com/sensei-hq/gateway) | Talk to every model provider through one Rust interface — fallback chains, circuit breaker, budgets | [gateway.sensei-hq.org](https://gateway.sensei-hq.org) |
| 構 | [dbd](https://github.com/sensei-hq/dbd) | Schema as SQL files: dependency order, migrations, data loading, docs and deploys across Postgres, Supabase, SQLite and Convex | [dbd.sensei-hq.org](https://dbd.sensei-hq.org) |
| 速 | [rokkit](https://github.com/sensei-hq/rokkit) | Composable, data-driven, themeable UI components for Svelte 5 | [rokkit.sensei-hq.org](https://rokkit.sensei-hq.org) |
| 守 | [kavach](https://github.com/sensei-hq/kavach) | Drop-in authentication for SvelteKit — sessions, providers, route protection | [kavach.sensei-hq.org](https://kavach.sensei-hq.org) |
| 絵 | [emaki](https://github.com/sensei-hq/emaki) | Illustrated stories for the web: articles, a story player and narrated video from one set of JSON scenes | [emaki.sensei-hq.org](https://emaki.sensei-hq.org) |

### Around the tools

| Repo | What |
|---|---|
| [sensei-releases](https://github.com/sensei-hq/sensei-releases) | Sensei release binaries · report a problem in its Issues |
| [marketplace](https://github.com/sensei-hq/marketplace) | The Sensei plugin that teaches AI assistants your codebase conventions (MIT) |
| [homebrew-tap](https://github.com/sensei-hq/homebrew-tap) | `brew install sensei` |

### Install Sensei (macOS)

```sh
brew tap sensei-hq/tap
brew install sensei-hq/tap/sensei          # CLI + daemon + MCP server
brew install --cask sensei-hq/tap/senseihq # Desktop app
```
