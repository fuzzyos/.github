<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://fuzzyos.com/assets/images/logo_text_light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://fuzzyos.com/assets/images/logo_text_dark.svg">
  <img alt="FuzzyOS" src="https://fuzzyos.com/assets/images/logo_text_dark.svg" height="48">
</picture>

**A minimal terminal coding harness — adapt fuzzy to your workflows, not the other way around.**

FuzzyOS ships with the essentials and stays out of your way. No opinionated sub-agents, no forced plan mode — just a lean, extensible core that works with 20+ AI providers and bends to however you actually work.

---

## Features

- **Minimal by default** — ships with `read`, `write`, `edit`, and `bash`. Nothing more until you need it.
- **Aggressively extensible** — TypeScript modules let you add custom tools, commands, keyboard shortcuts, and UI components.
- **Skills** — on-demand capability packages invoked via `/skill:name`, following the Agent Skills standard.
- **Sessions & branching** — JSONL-backed session trees; navigate history and branch from any prior point.
- **Fuzzy Packages** — shareable bundles installable via npm or git.
- **Multi-provider** — Anthropic Claude, OpenAI, Google Gemini, and 20+ other providers through a unified API.
- **Multiple execution modes** — interactive TUI, print/JSON for scripting, RPC for process integration, Node.js SDK for embedding.
- **VS Code integration** — sidebar panel, automatic file context, and native UI component support.

---

## Packages

| Package | Description |
|---|---|
| [`@fuzzyos/fuzzy-code`](https://github.com/fuzzyos/fuzzyos) | Core interactive CLI coding harness |
| [`@fuzzyos/fuzzy-code-vsce`](https://github.com/fuzzyos/fuzzy-code-vsce) | VS Code extension for the fuzzy-code CLI |
| [`@fuzzyos/fuzzy-ai`](https://github.com/fuzzyos/fuzzyos) | Unified API across 20+ LLM providers |
| [`@fuzzyos/fuzzy-agent`](https://github.com/fuzzyos/fuzzyos) | Agent runtime: tool invocation and state tracking |
| [`@fuzzyos/fuzzy-tui`](https://github.com/fuzzyos/fuzzyos) | Terminal UI framework with efficient screen rendering |
| [`@fuzzyos/fuzzy-web-ui`](https://github.com/fuzzyos/fuzzyos) | Web components for conversational AI interfaces |
| [`@fuzzyos/fuzzy-pods`](https://github.com/fuzzyos/fuzzyos) | vLLM deployment management on GPU compute |

---

## Install

```bash
npm install -g @fuzzyos/fuzzy-code
```

Then set your API key and run `fuzzy` to start.

---

## Tech Stack

- **TypeScript** — primary language across all packages
- **Nix** — reproducible build and development environments
- **MIT License** — all repositories are open source

---

## Contact

[contact@fuzzyos.com](mailto:contact@fuzzyos.com) · [fuzzyos.com](https://fuzzyos.com)
