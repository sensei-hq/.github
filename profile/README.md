# Sensei  先生

**Observe. Learn. Improve.**

Sensei is a development intelligence platform for AI-assisted coding. It watches your coding sessions, learns your team's patterns and conventions, and feeds that knowledge back to your AI assistant — so it gets it right the first time.

---

### How it works

A background daemon indexes your codebase — files, symbols, relationships, patterns. As you work with AI coding assistants, sensei tracks what works, catches what drifts, and builds a living model of how your project is built.

Your AI assistant queries sensei through MCP to ground its suggestions in your actual codebase — not guesses from training data.

### Repos

| Repo | What | Stack |
|------|------|-------|
| [sensei](https://github.com/sensei-hq/sensei) | **Monorepo** — daemon, desktop app, CLI, MCP server, gateway, website | Rust + Tauri + SvelteKit |
| [marketplace](https://github.com/sensei-hq/marketplace) | Plugin that teaches AI assistants your codebase conventions | Claude Code plugin |
| [homebrew-tap](https://github.com/sensei-hq/homebrew-tap) | `brew install sensei` — one command to get started | Homebrew |
| [dbd](https://github.com/sensei-hq/dbd) | Schema-first database tool — DDL, migrations, seeding | Rust |
| [corpus](https://github.com/sensei-hq/corpus) | Test repos for measuring indexing and coaching accuracy | Multi-language |

### Install (macOS)

```sh
brew tap sensei-hq/tap
brew install sensei-hq/tap/sensei     # CLI + daemon
brew install sensei-hq/tap/senseihq   # Desktop app
```
