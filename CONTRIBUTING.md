# Contributing to AgenticMarket MCP Servers

Thanks for contributing. This list is community-maintained - every PR that adds a real, working server gets merged within 24 hours.

---

## How to Add Your Server

### Requirements

Before submitting, make sure your server:

- [ ] Is live on [AgenticMarket](https://agenticmarket.dev) approved and publicly installable
- [ ] Has a working install command (`agenticmarket install username/server-name`)
- [ ] Has a public listing page on agenticmarket.dev

### Steps

1. **Fork** this repository
2. **Edit `README.md`** — find the right category for your server
3. **Add a row** to the table in this format:

```markdown
| [server-name](https://agenticmarket.dev/skills/username/server-name) | One-line description of what it does | `agenticmarket install username/server-name` |
```

**Description rules:**
- One sentence, max 80 characters
- Start with a verb: "Fetch", "Search", "Query", "Generate", "Convert"
- No marketing language just what it does

4. **Open a PR** with the title: `Add: username/server-name`

---

## Categories

Add your server to the most relevant section. If your server fits multiple categories, pick the primary one.

| Category | What belongs here |
|----------|------------------|
| AI | Artificial intelligence, machine learning, LLMs |
| Automation | Automated workflows, bots, triggers |
| Developer Tools | Code tools, formatters, validators, converters |
| Data Processing | ETL, data pipelines, analytics |
| Search | Search engines, data fetching |
| Productivity | Tasks, calendars, notes, project management |
| Research | Research tools, academic, discovery |
| Content Generation | Text, image, video, audio generation |
| DevOps | CI/CD, deployment, infrastructure |
| Integrations | API connectors, service bridges |
| Finance | Market data, crypto, analytics platforms |
| Education | Learning, teaching, study tools |
| Utilities | Miscellaneous tools, helpers |
| other | Anything that doesn't fit above |

If your category doesn't exist yet, add a new section — follow the same `### 🔤 Category Name` format.

---

## What Gets Rejected

- Servers not yet live on AgenticMarket
- Duplicate entries
- Broken install commands
- Descriptions longer than one sentence or containing marketing language
- Servers that violate [AgenticMarket's Terms of Service](https://agenticmarket.dev/terms)

---

## Request a Server

Not a creator but want a specific server to exist?

[Open a Server Request issue](https://github.com/agenticmarket/mcp-servers/issues/new?template=server-request.md)

Creators browse these requests to find what to build next.

---

## Questions

[support@agenticmarket.dev](mailto:support@agenticmarket.dev)
