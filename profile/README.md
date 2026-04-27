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
| [daemon](https://github.com/sensei-hq/daemon) | Core engine — indexer, CLI, MCP server | Rust |
| [app](https://github.com/sensei-hq/app) | Desktop observatory | Tauri + SvelteKit |
| [gateway](https://github.com/sensei-hq/gateway) | Multi-provider LLM router | Rust |
| [marketplace](https://github.com/sensei-hq/marketplace) | Skills, commands, agents, hooks | Claude Code plugin |
| [website](https://github.com/sensei-hq/website) | Marketing site | SvelteKit |
| [homebrew-tap](https://github.com/sensei-hq/homebrew-tap) | macOS distribution | Homebrew |
| [releases](https://github.com/sensei-hq/releases) | Binary releases | CI artifacts |
| [corpus](https://github.com/sensei-hq/corpus) | Benchmark test repos | Multi-language |
| [docs](https://github.com/sensei-hq/docs) | Design docs, roadmap, architecture | Markdown |

### Status

Sensei is in active development and not yet released. The daemon indexes code and serves an MCP interface, the desktop app structure is in place, and the marketplace plugin defines the full workflow. We're working toward a first public release.

### Install (when available)

```sh
brew install sensei-hq/tap/sensei
sensei init
```
