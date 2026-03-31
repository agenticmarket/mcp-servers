# ✦ AgenticMarket — MCP Server Registry

MCP servers are spread across repositories and often require manual setup.
AgenticMarket helps you discover, install, and publish MCP servers in one command for Cursor, VS Code, and Claude Desktop.

```bash
npm install -g agenticmarket
agenticmarket install username/server-name
```

---

Supports:

- Cursor MCP servers
- Claude Desktop MCP integrations
- VS Code MCP tools

## What is AgenticMarket MCP Server Registry?

AgenticMarket is a registry for discovering, installing, and publishing MCP servers for MCP-compatible clients such as Cursor, VS Code, and Claude Desktop.

- **For users** — install any MCP server instantly, pay per call
- **For creators** — publish once, earn on every call, no infrastructure needed

## What you can do with AgenticMarket

- Install MCP servers instantly using CLI
- Discover ready-to-use MCP tools
- Connect AI apps (Cursor, Claude, VS Code) to external systems
- Publish and monetize your own MCP server

## What is the Model Context Protocol (MCP)?

Model Context Protocol (MCP) is an open-source standard for connecting AI applications to external systems. Using MCP, AI applications like Claude or ChatGPT can connect to data sources (e.g. local files, databases), tools (e.g. search engines, calculators) and workflows (e.g. specialized prompts)—enabling them to access key information and perform tasks.

Think of MCP like a USB-C port for AI applications. Just as USB-C provides a standardized way to connect electronic devices, MCP provides a standardized way to connect AI applications to external systems.

**[→ Official docs](https://modelcontextprotocol.io/docs/getting-started/intro)**

---

## Servers

### 🔎 Search

| Server                                                                   | Description                                                                                                                                               | Install                                              |
| ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| [web-reader](https://agenticmarket.dev/agenticmarket/web-reader)         | Extract readable content from webpages, removing ads and clutter                                                                                          | `agenticmarket install agenticmarket/web-reader`     |
| [rss-reader](https://agenticmarket.dev/agenticmarket/rss-reader)         | Fetch and parse RSS/Atom feeds to retrieve latest articles and updates                                                                                    | `agenticmarket install agenticmarket/rss-reader`     |
| [sitemap-reader](https://agenticmarket.dev/agenticmarket/sitemap-reader) | Fetch and parse XML sitemaps for site discovery and crawling                                                                                              | `agenticmarket install agenticmarket/sitemap-reader` |
| [site-metadata](https://agenticmarket.dev/agenticmarket/site-metadata)   | Extract metadata, OG tags, and structured info from any URL                                                                                               | `agenticmarket install agenticmarket/site-metadata`  |
| [wikipedia](https://agenticmarket.dev/agenticmarket/wikipedia)           | Extract articles and retrieve full content, making it easy for AI agents to access reliable, structured knowledge.                                        | `agenticmarket install genticmarket/wikipedia`       |
| [hackernews](https://agenticmarket.dev/agenticmarket/hackernews)         | Fetch top stories, individual posts with comments, and the latest Ask HN / Show HN discussions — all in a clean, structured format that’s easy for agents | `agenticmarket install genticmarket/hackernews`      |
| [duckduckgo](https://agenticmarket.dev/agenticmarket/duckduckgo)         | Provides structured search results (title, URL, snippet) via a simple MCP-compatible API, optimized for fast integration into LLM workflows.              | `agenticmarket install genticmarket/duckduckgo`      |

### 🛠 Developer Tools

| Server                                                                   | Description                                              | Install                                              |
| ------------------------------------------------------------------------ | -------------------------------------------------------- | ---------------------------------------------------- |
| [json-tools](https://agenticmarket.dev/agenticmarket/json-tools)         | Validate, format, query, and transform JSON data         | `agenticmarket install agenticmarket/json-tools`     |
| [markdown-fetch](https://agenticmarket.dev/agenticmarket/markdown-fetch) | Fetch remote markdown content from URLs and repositories | `agenticmarket install agenticmarket/markdown-fetch` |
| [url-status](https://agenticmarket.dev/agenticmarket/url-status)         | Check URL reachability and HTTP status for any endpoint  | `agenticmarket install agenticmarket/url-status`     |

### 📊 Data Processing

| Server                                                               | Description                                                             | Install                                            |
| -------------------------------------------------------------------- | ----------------------------------------------------------------------- | -------------------------------------------------- |
| [text-cleaner](https://agenticmarket.dev/agenticmarket/text-cleaner) | Clean and normalize text by removing HTML tags, scripts, and whitespace | `agenticmarket install agenticmarket/text-cleaner` |

### 🔧 Utilities

| Server                                                 | Description                                                                       | Install                                     |
| ------------------------------------------------------ | --------------------------------------------------------------------------------- | ------------------------------------------- |
| [utils](https://agenticmarket.dev/agenticmarket/utils) | Lightweight utilities — greeting, jokes, fun facts, UUID, random color generation | `agenticmarket install agenticmarket/utils` |

### 💰 Finance

| Server                                                                 | Description                                     | Install                                              |
| ---------------------------------------------------------------------- | ----------------------------------------------- | ---------------------------------------------------- |
| [exchange-rate](https://agenticmarket.dev/agenticmarket/exchange-rate) | A simple MCP server for currency exchange data. | `agenticmarket install @agenticmarket/exchange-rate` |

---

## Install MCP Servers in One Command

```bash
# 1. Install the CLI
npm install -g agenticmarket

# 2. Authenticate
agenticmarket auth YOUR_API_KEY

# 3. Install any server
agenticmarket install agenticmarket/web-reader

# 4. Open VS Code, Cursor, or Claude Desktop — the tool is ready
```

Get your API key at [agenticmarket.dev](https://agenticmarket.dev/dashboard/api-keys)

---

## Publish Your MCP Server

Already built an MCP server? List it on AgenticMarket - it's free.

**What you need:**

- A publicly accessible HTTPS endpoint (HTTP-based MCP)
- A free AgenticMarket account

**[→ Submit your server](https://agenticmarket.dev/dashboard/submit)**

> 🌟 **Founding Creator program** — first 100 approved creators earn **90% per call** for 12 months. Slots are limited.

---

## Add Your Server to This List

If your server is live on AgenticMarket, open a PR to add it here.

1. Fork this repo
2. Add your server to the correct category in `README.md`
3. Follow the table format — Name | Description | Install command
4. Open a PR with the title: `Add: username/server-name`

See [CONTRIBUTING.md](./CONTRIBUTING.md) for full guidelines.

---

## Request a Server

Don't see a server you need? [Open an issue](https://github.com/agenticmarket/mcp-servers/issues/new?template=server-request.md) and describe what you're looking for. Creators browse requests.

---

## Links

- [agenticmarket.dev](https://agenticmarket.dev) — browse and install
- [CLI on npm](https://www.npmjs.com/package/agenticmarket) — `npm install -g agenticmarket`
- [Docs](https://agenticmarket.dev/docs) — full documentation
- [Publish your server](https://agenticmarket.dev/dashboard/submit) — creator onboarding
- [Pricing](https://agenticmarket.dev/pricing) — credits and creator earnings

---

Maintained by the [AgenticMarket](https://agenticmarket.dev) team · [support@agenticmarket.dev](mailto:support@agenticmarket.dev)
Licensed under [CC0 1.0](./LICENSE) - public domain
