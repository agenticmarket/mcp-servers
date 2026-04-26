# ✦ AgenticMarket — MCP Server Registry

MCP servers are spread across repositories and often require manual setup.
AgenticMarket helps you discover, install, and publish MCP servers in one command for Cursor, VS Code, Claude Desktop, and more.

```bash
npm install -g agenticmarket

# Install a server from /servers
agenticmarket install username/server-name

# Install a community server from /explore
agenticmarket install server-slug
```

---

Supports:

- VS Code MCP tools
- Cursor MCP servers
- Claude Desktop MCP integrations
- Claude Code
- Windsurf
- Gemini CLI
- Github Copilot
- Zed
- Cline
- Codex
- Antigravity

## What is AgenticMarket MCP Server Registry?

AgenticMarket is a registry for discovering, installing, and publishing MCP servers for MCP-compatible clients such as Cursor, VS Code, Claude Desktop, Antigravity, and more.

- **For users** — install any MCP server instantly, pay per call
- **For creators** — publish once, earn on every call, no infrastructure needed

## What you can do with AgenticMarket

- Install MCP servers instantly using CLI
- Discover ready-to-use MCP tools
- Connect AI apps (Cursor, Claude, VS Code) to external systems
- Publish and monetize your own MCP server
- List any MCP server in the community directory — open source or otherwise

## What is the Model Context Protocol (MCP)?

Model Context Protocol (MCP) is an open-source standard for connecting AI applications to external systems. Using MCP, AI applications like Claude or ChatGPT can connect to data sources (e.g. local files, databases), tools (e.g. search engines, calculators) and workflows (e.g. specialized prompts)—enabling them to access key information and perform tasks.

Think of MCP like a USB-C port for AI applications. Just as USB-C provides a standardized way to connect electronic devices, MCP provides a standardized way to connect AI applications to external systems.

**[→ Official docs](https://modelcontextprotocol.io/docs/getting-started/intro)**

---

## Servers

### 🔎 Search

| Server                                                                         | Description                                                                                                                        | Install                                             |
| ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| [web-reader](https://agenticmarket.dev/agenticmarket/web-reader)       | Extract readable content from webpages, removing ads and clutter                                                                   | `agenticmarket install agenticmarket/web-reader`    |
| [rss-reader](https://agenticmarket.dev/agenticmarket/rss-reader)       | Fetch and parse RSS/Atom feeds to retrieve latest articles and updates                                                             | `agenticmarket install agenticmarket/rss-reader`    |
| [site-metadata](https://agenticmarket.dev/agenticmarket/site-metadata) | Extract metadata, OG tags, and structured info from any URL                                                                        | `agenticmarket install agenticmarket/site-metadata` |
| [wikipedia](https://agenticmarket.dev/agenticmarket/wikipedia)         | Extract articles and retrieve full content, making it easy for AI agents to access reliable, structured knowledge                  | `agenticmarket install agenticmarket/wikipedia`     |
| [hackernews](https://agenticmarket.dev/agenticmarket/hackernews)       | Fetch top stories, individual posts with comments, and the latest Ask HN / Show HN discussions — all in a clean, structured format | `agenticmarket install agenticmarket/hackernews`    |
| [duckduckgo](https://agenticmarket.dev/agenticmarket/duckduckgo)       | Structured search results (title, URL, snippet) via a simple MCP-compatible API, optimized for LLM workflows                       | `agenticmarket install agenticmarket/duckduckgo`    |

### 📈 SEO

| Server                                                                                       | Description                                                                                                    | Install                                                    |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| [sitemap-reader](https://agenticmarket.dev/agenticmarket/sitemap-reader)             | Fetch and parse XML sitemaps for site discovery and crawling                                                   | `agenticmarket install agenticmarket/sitemap-reader`       |
| [robots-sitemap-audit](https://agenticmarket.dev/agenticmarket/robots-sitemap-audit) | Analyze robots.txt and sitemap configuration to ensure proper crawling, indexing, and search engine visibility | `agenticmarket install agenticmarket/robots-sitemap-audit` |
| [seo-audit](https://agenticmarket.dev/agenticmarket/seo-audit)                       | Analyze any webpage's on-page SEO and return a detailed score with actionable recommendations                  | `agenticmarket install agenticmarket/seo-audit`            |

### 🛠 Developer Tools

| Server                                                                           | Description                                                                                                                     | Install                                              |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| [json-tools](https://agenticmarket.dev/agenticmarket/json-tools)         | Validate, format, query, and transform JSON data                                                                                | `agenticmarket install agenticmarket/json-tools`     |
| [markdown-fetch](https://agenticmarket.dev/agenticmarket/markdown-fetch) | Fetch remote markdown content from URLs and repositories                                                                        | `agenticmarket install agenticmarket/markdown-fetch` |
| [dev-toolkit](https://agenticmarket.dev/agenticmarket/dev-toolkit)       | Essential developer utilities for generating UUIDs, hashing text, decoding JWTs, comparing versions, and testing regex patterns | `agenticmarket install agenticmarket/dev-toolkit`    |
| [url-status](https://agenticmarket.dev/agenticmarket/url-status)         | Check URL reachability and HTTP status for any endpoint                                                                         | `agenticmarket install agenticmarket/url-status`     |

### 🗄️ Database

| Server                                                               | Description                                                                                       | Install                                     |
| -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| [crypto-info](https://agenticmarket.dev/fiowind/crypto-info) | Real-time prices, 24h volume, and price changes for top cryptocurrencies, plus latest market news | `agenticmarket install fiowind/crypto-info` |

### 📊 Data Processing

| Server                                                                       | Description                                                             | Install                                            |
| ---------------------------------------------------------------------------- | ----------------------------------------------------------------------- | -------------------------------------------------- |
| [text-cleaner](https://agenticmarket.dev/agenticmarket/text-cleaner) | Clean and normalize text by removing HTML tags, scripts, and whitespace | `agenticmarket install agenticmarket/text-cleaner` |

### 🔧 Utilities

| Server                                                         | Description                                                                       | Install                                     |
| -------------------------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------- |
| [utils](https://agenticmarket.dev/agenticmarket/utils) | Lightweight utilities — greeting, jokes, fun facts, UUID, random color generation | `agenticmarket install agenticmarket/utils` |

### 💰 Finance

| Server                                                                         | Description                                    | Install                                             |
| ------------------------------------------------------------------------------ | ---------------------------------------------- | --------------------------------------------------- |
| [exchange-rate](https://agenticmarket.dev/agenticmarket/exchange-rate) | A simple MCP server for currency exchange data | `agenticmarket install agenticmarket/exchange-rate` |

---

## Explore (community listed)

Browse servers listed by the community at [agenticmarket.dev/explore](https://agenticmarket.dev/explore).

Anyone with an AgenticMarket account can list any publicly accessible MCP server — open source, personal projects, or anything in between.

### 🔎 Search

| Server                                                                 | Description                                                                                                         | Install                                  |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| [Fetch MCP Server](https://agenticmarket.dev/explore/fetch-mcp-server) | Give your AI assistant the ability to read any web page. The official Fetch server converts HTML to markdown by MCP | `agenticmarket install fetch-mcp-server` |

### 📁 File System

| Server                                                                           | Description                                                                                                                                               | Install                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| [Filesystem MCP Server](https://agenticmarket.dev/explore/filesystem-mcp-server) | Give your AI assistant read and write access to local files and directories. The most-used MCP server — lets AI tools work with your filesystem directly. | `agenticmarket install filesystem-mcp-server` |

### 🔧 Utilities

| Server                                                               | Description                                                                                                                                                           | Install                                 |
| -------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| [Time MCP Server](https://agenticmarket.dev/explore/time-mcp-server) | Give your AI assistant awareness of the current time and timezone conversions. Query the current time in any timezone and convert between timezones using IANA names. | `agenticmarket install time-mcp-server` |

### 🛠 Developer Tools

| Server                                                                           | Description                                                                                                                                                                     | Install                                       |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| [Everything MCP Server](https://agenticmarket.dev/explore/everything-mcp-server) | The official MCP reference server that exercises every protocol feature — prompts, tools, resources, sampling, and all transports. Built for MCP client developers and testing. | `agenticmarket install everything-mcp-server` |
| [Git MCP Server](https://agenticmarket.dev/explore/git-mcp-server)               | Let your AI assistant interact with Git repositories directly. Status, diff, commit, branch, and log — all accessible to your LLM through 12 Git tools.                         | `agenticmarket install git-mcp-server`        |

### ✨ AI-ML

| Server                                                                                  | Description                                                                                                                                                                              | Install                                                |
| --------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| [Sequential Thinking](https://agenticmarket.dev/explore/sequential-thinking-mcp-server) | Enhance your AI assistant's reasoning with structured, step-by-step thinking. Supports revisions, branching, and dynamic adjustment of reasoning depth.                                  | `agenticmarket install sequential-thinking-mcp-server` |
| [Memory](https://agenticmarket.dev/explore/memory-mcp-server)                           | Give your AI assistant persistent memory across conversations. The Memory server stores entities, relations, and observations in a local knowledge graph that persists between sessions. | `agenticmarket install memory-mcp-server`              |

```bash
# Install any community server by slug
agenticmarket install server-slug
```

---

## Install MCP Servers in One Command

### From /servers

```bash
# 1. Install the CLI
npm install -g agenticmarket

# 2. Authenticate
agenticmarket auth YOUR_API_KEY

# 3. Install any server
agenticmarket install username/server-name

# 4. Open VS Code, Cursor, Claude Desktop or other IDE — the tool is ready
```

### From /explore (community)

```bash
# 1. Install the CLI
npm install -g agenticmarket

# 2. Authenticate
agenticmarket auth YOUR_API_KEY

# 3. Install any community server by slug
agenticmarket install server-slug

# 4. Open VS Code, Cursor, Claude Desktop or other IDE — the tool is ready
```

Get your API key at [agenticmarket.dev](https://agenticmarket.dev/dashboard/api-keys)

---

## Publish Your MCP Server

### Monetize it on /servers

Already built an MCP server with a public HTTPS endpoint? List it on AgenticMarket and earn on every call.

**What you need:**

- A publicly accessible HTTPS endpoint (HTTP-based MCP)
- A free AgenticMarket account

**[→ Submit your server](https://agenticmarket.dev/dashboard/submit)**

> 🌟 **Founding Creator program** — first 100 approved creators earn **90% per call** for 12 months. Slots are limited.

### List it on /explore (community)

Want to share a server with the community without monetization? List it on Explore — no HTTPS requirement, open source or otherwise.

**[→ List on Explore](https://agenticmarket.dev/explore/submit)**

---

## Add Your Server to This List

If your server is live on AgenticMarket, open a PR to add it here.

1. Fork this repo
2. Add your server to the correct category in `README.md`
3. Follow the table format — Name | Description | Install command
4. Open a PR with the title: `Add server: username/server-slug`

See [CONTRIBUTING.md](./CONTRIBUTING.md) for full guidelines.

---

## Request a Server

Don't see a server you need? [Open an issue](https://github.com/agenticmarket/mcp-servers/issues/new?template=server-request.md) and describe what you're looking for. Creators browse requests.

---

## Links

- [agenticmarket.dev](https://agenticmarket.dev) — browse and install
- [Explore](https://agenticmarket.dev/explore) — community server directory
- [CLI on npm](https://www.npmjs.com/package/agenticmarket) — `npm install -g agenticmarket`
- [Docs](https://agenticmarket.dev/docs) — full documentation
- [Publish your server](https://agenticmarket.dev/dashboard/submit) — creator onboarding
- [Submit Community server](https://agenticmarket.dev/explore/submit) — creator onboarding
- [Pricing](https://agenticmarket.dev/pricing) — Pricing page

---

Maintained by the [AgenticMarket](https://agenticmarket.dev) team · [support@agenticmarket.dev](mailto:support@agenticmarket.dev)
Licensed under [CC0 1.0](./LICENSE) - public domain
