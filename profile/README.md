# Sensei HQ  先生

**An independent studio of developer tools.**

Each tool has a single job and a clear edge. Local-first wherever it makes sense, quiet by default,
and the libraries our products stand on are open source. → [sensei-hq.com](https://sensei-hq.com)

---

### Products — things you open

| | Repo | What | Stack |
|---|------|------|-------|
| 観 | [sensei](https://github.com/sensei-hq/sensei) | **Sensei** — a quiet companion for AI-assisted work: observes your sessions and surfaces the patterns you are too close to see. Daemon, desktop app, CLI, MCP server and the Dōjō team console | Rust · Tauri · SvelteKit |
| 門 | [torii](https://github.com/sensei-hq/torii) | **Torii** — every model, one governed doorway: an AI gateway for teams, with budgets, fallback chains and guardrails | Rust · SvelteKit |

### Libraries — things you build on

| | Repo | What | Stack |
|---|------|------|-------|
| 関 | [gateway](https://github.com/sensei-hq/gateway) | Talk to every model provider through one interface — fallback chains, circuit breaker, budgets | Rust |
| 構 | [dbd](https://github.com/sensei-hq/dbd) | Schema as SQL files: dependency order, migrations, data loading, docs and deploys across Postgres, Supabase, SQLite and Convex | Rust |
| 速 | [rokkit](https://github.com/sensei-hq/rokkit) | Composable, data-driven, themeable UI components | Svelte 5 |
| 守 | [kavach](https://github.com/sensei-hq/kavach) | Drop-in authentication for SvelteKit — sessions, providers, route protection | TypeScript |

### Still taking shape

| | Repo | What | |
|---|------|------|---|
| 形 | [katachi](https://github.com/sensei-hq/katachi) | From a photo to a cut — snap a sketch, say what you want, get measured, cut-ready parts | Preview · [try it](https://katachi.sensei-hq.com) |
| 型 | [kata](https://github.com/sensei-hq/kata) | Training that meets you where you are — AI-programmed workouts that adapt to your progress | Incubating |

### Around the tools

| Repo | What |
|------|------|
| [marketplace](https://github.com/sensei-hq/marketplace) | The Sensei plugin that teaches AI assistants your codebase conventions |
| [homebrew-tap](https://github.com/sensei-hq/homebrew-tap) | `brew install sensei` — one command to get started |
| [website](https://github.com/sensei-hq/website) | [sensei-hq.com](https://sensei-hq.com) |

### Install Sensei (macOS)

```sh
brew tap sensei-hq/tap
brew install sensei-hq/tap/sensei          # CLI + daemon + MCP server
brew install --cask sensei-hq/tap/senseihq # Desktop app
```
