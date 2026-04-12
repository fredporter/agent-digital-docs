---
layout: page
title: Linkdown — Quick start
permalink: /support/linkdown/quick-start.html
---

**Scope — Linkdown Core (free):** Steps 1–5 are the public **AGPL** app. Step 6 involves Premium and/or external MCP servers — see below.

1. **Install Linkdown** — Use release builds from the [Linkdown-core](https://github.com/fredporter/Linkdown-core) project when published, or build from source (see repository `README` and `CONTRIBUTING`).
2. **Choose a vault folder** — On first launch, pick an empty folder or an existing notes directory. With **Master vault** enabled (Settings → Linkdown features), the app can scaffold `Binders/`, `Data/`, `.linkdown/`, and related layout for compatibility with Obsidian-style workflows.
3. **Create a note** — Use the sidebar **+** or folder menu → **New document**. Notes are Markdown on disk.
4. **Preview** — Split or preview mode renders **GitHub Flavored Markdown** plus Linkdown extensions (Mermaid, Shiki code highlighting in preview, math where enabled, etc.).
5. **Optional: chat & models** — Enable **LLM & connectors** in Settings, add API keys for OpenAI / Anthropic / compatible endpoints, then use the chat panel (Core uses **your** keys).

> **Linkdown Premium required:** The **built-in** premium MCP tool runtime (merged builtin + premium orchestration in the private module) is **not** in the stock open-source build. You need [Linkdown-premium](https://github.com/fredporter/Linkdown-premium), host env vars, and any licence your distribution uses. The free app may still use an MCP **client** to **external** stdio servers via `Data/mcp/servers.json` where documented.

6. **Optional: MCP** — External servers: configure `Data/mcp/servers.json`. Premium builtins and full runtime: see [Premium & MCP](premium-mcp.html) and [Quick start](https://github.com/fredporter/Linkdown-core/blob/main/docs/guide/QUICK_START.md) in Linkdown-core.

**Next:** [Interface overview](interface.html) · [Vault & tasks](vault-and-tasks.html)
