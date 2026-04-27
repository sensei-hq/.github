# Sensei  先生

**Observe. Learn. Improve.**

Sensei is a development intelligence platform for AI-assisted coding. It watches your coding sessions, learns your team's patterns and conventions, and feeds that knowledge back to your AI assistant — so it gets it right the first time.

---

### How it works

A background daemon indexes your codebase — files, symbols, relationships, patterns. As you work with AI coding assistants, sensei tracks what works, catches what drifts, and builds a living model of how your project is built.

Your AI assistant queries sensei through MCP to ground its suggestions in your actual codebase — not guesses from training data.

### What's in this org

| Repo | What | Stack |
|------|------|-------|
| [daemon](https://github.com/sensei-hq/daemon) | Indexes your codebase, detects patterns, serves intelligence to AI assistants | Rust |
| [app](https://github.com/sensei-hq/app) | See how AI builds your code — sessions, patterns, quality trends | Tauri + SvelteKit |
| [gateway](https://github.com/sensei-hq/gateway) | Route AI requests across providers with fallbacks and cost control | Rust |
| [marketplace](https://github.com/sensei-hq/marketplace) | Plugin that teaches AI assistants your codebase conventions | Claude Code plugin |
| [homebrew-tap](https://github.com/sensei-hq/homebrew-tap) | `brew install sensei` — one command to get started | Homebrew |
| [corpus](https://github.com/sensei-hq/corpus) | Test repos for measuring indexing and coaching accuracy | Multi-language |

### Status

Sensei is in active development and not yet released. The daemon indexes code and serves an MCP interface, the desktop app structure is in place, and the marketplace plugin defines the full workflow. We're working toward a first public release.

### Install (when available)

```sh
brew install sensei-hq/tap/sensei
sensei init
```
