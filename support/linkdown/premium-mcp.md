---
layout: page
title: Linkdown — Premium & MCP
permalink: /support/linkdown/premium-mcp.html
---

**Scope — Linkdown Premium:** This page is about the **paid/proprietary** add-on and how it differs from Core. For Core-only behaviour, see [Quick start](quick-start.html) and the [Linkdown-core docs](https://github.com/fredporter/Linkdown-core/tree/main/docs).

## Free vs premium (summary)

- **Linkdown Core (AGPL)** — Full editor and vault; can connect to your own API keys for chat; includes an MCP **client** path for configured servers where supported.
- **Linkdown Premium (proprietary)** — Adds the **premium MCP runtime**, extended automation, publishing workflows, and related features. Builds and licensing are described in the private **Linkdown-premium** repository and family configuration docs in the core repo.

For a concise boundary table, see [V30_FREE_PREMIUM_BOUNDARY.md](https://github.com/fredporter/Linkdown-core/blob/main/docs/V30_FREE_PREMIUM_BOUNDARY.md) in Linkdown-core.

## MCP configuration (high level)

Users can configure **stdio MCP servers** via `Data/mcp/servers.json` inside the vault when that feature is available in your build. Premium builds merge **built-in vault tools** with external MCP servers. Stock open-source builds may show premium stubs for certain tool entry points unless a premium module is loaded at runtime.

**Technical detail:** [LINKDOWN_PREMIUM_MCP_SCHEMA.md](https://github.com/fredporter/Linkdown-core/blob/main/docs/LINKDOWN_PREMIUM_MCP_SCHEMA.md) (maintainer-oriented).

**Back:** [Support home](index.html) · [Get help](get-help.html)
