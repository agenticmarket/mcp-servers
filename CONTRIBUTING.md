# Contributing to AgenticMarket MCP Servers

Thanks for contributing. This list is community-maintained — every PR that adds a real, working server gets merged within 24 hours.

---

## Two Ways to Add Your Server

### /servers — Monetized listing

For MCP servers you own with a public HTTPS endpoint. Users install via CLI and you earn per call.

**Requirements:**

- [ ] Server is live and approved on [AgenticMarket /servers](https://agenticmarket.dev/servers)
- [ ] Install command works: `agenticmarket install username/server-name`
- [ ] Public listing exists at `agenticmarket.dev/servers/username/server-name`

**Add a row to the correct category table:**

```markdown
| [server-name](https://agenticmarket.dev/servers/username/server-name) | One-line description of what it does | `agenticmarket install username/server-name` |
```

---

### /explore — Community listing

For any publicly accessible MCP server — open source, personal projects, or anything else. No monetization required.

**Requirements:**

- [ ] Server is listed on [AgenticMarket /explore](https://agenticmarket.dev/explore)
- [ ] Install command works: `agenticmarket install server-slug`
- [ ] Public listing exists at `agenticmarket.dev/explore/server-slug`

**Add a row under the Explore section:**

```markdown
| [server-name](https://agenticmarket.dev/explore/server-slug) | One-line description of what it does | `agenticmarket install server-slug` |
```

---

## Steps

1. **Fork** this repository
2. **Edit `README.md`** — find the right section and category for your server
3. **Add a row** using the format above
4. **Open a PR** with the title:
   - `/servers` submission: `Add: username/server-name`
   - `/explore` submission: `Add: server-slug`

**Description rules:**

- One sentence, max 80 characters
- Start with a verb: "Fetch", "Search", "Query", "Generate", "Convert"
- No marketing language — just what it does

---

## Categories

Add your server to the most relevant section. If your server fits multiple categories, pick the primary one.

| Category           | What belongs here                               |
| ------------------ | ----------------------------------------------- |
| AI-ML              | Artificial intelligence, machine learning, LLMs |
| Automation         | Automated workflows, bots, triggers             |
| Developer Tools    | Code tools, formatters, validators, converters  |
| Data Processing    | ETL, data pipelines, analytics                  |
| Search             | Search engines, data fetching                   |
| SEO                | SEO audits, indexing, crawling, and optimization |
| Database           | Databases, SQL, storage engines, and data access |
| Productivity       | Tasks, calendars, notes, project management     |
| Research           | Research tools, academic, discovery             |
| File System        | File and Folder discovery                       |
| Content Generation | Text, image, video, audio generation            |
| DevOps             | CI/CD, deployment, infrastructure               |
| Integrations       | API connectors, service bridges                 |
| Finance            | Market data, crypto, analytics platforms        |
| Education          | Learning, teaching, study tools                 |
| Utilities          | Miscellaneous tools, helpers                    |
| Cloud              | Cloud services, hosting, serverless, and infra APIs |
| Communication      | Messaging, email, notifications, and collaboration |
| Monitoring         | Observability, logs, metrics, and alerting      |
| Other              | Anything that doesn't fit above                 |

If your category doesn't exist yet, add a new section — follow the same `### 🔤 Category Name` format.

---

## What Gets Rejected

- Servers not yet live on AgenticMarket (either /servers or /explore)
- Duplicate entries
- Broken install commands
- Descriptions longer than one sentence or containing marketing language
- Servers that violate [AgenticMarket's Terms of Service](https://agenticmarket.dev/terms)

---

## Report a Problem

Found a broken install command, wrong description, or a server that's been removed?

[Open a Server Issue](https://github.com/agenticmarket/mcp-servers/issues/new?template=server-issue.md)

---

## Request a Server

Not a creator but want a specific server to exist?

[Open a Server Request](https://github.com/agenticmarket/mcp-servers/issues/new?template=server-request.md)

Creators browse these requests to find what to build next.

---

## Questions

[support@agenticmarket.dev](mailto:support@agenticmarket.dev)
