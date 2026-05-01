# Hi, I'm Olga

I build tools for AI-assisted development, focusing on MCP servers and Claude Code skills.

## Featured Projects

### SkillCheck

Validate Claude Code skills against the [agentskills specification](https://agentskills.io).

- **[SkillCheck Free](https://github.com/olgasafonova/SkillCheck-Free)** - Skill-based validator (MIT)
- **[SkillCheck Pro](https://getskillcheck.com)** - MCP server with anti-slop, security, WCAG checks

### MCP Servers

MCP servers for whiteboards, wikis, roadmaps, registries, financial data, architecture, and grocery deals:

- **[miro-mcp-server](https://github.com/olgasafonova/miro-mcp-server)** - Build boards, sticky grids, and Mermaid diagrams from conversation instead of dragging shapes one by one
- **[mediawiki-mcp-server](https://github.com/olgasafonova/mediawiki-mcp-server)** - Find, edit, and audit wiki content from AI conversation. Catch broken links and stale pages automatically. Search inside pages and uploaded files. Bulk-replace terms across categories
- **[productplan-mcp-server](https://github.com/olgasafonova/productplan-mcp-server)** - Pull roadmap status, OKR progress, and idea backlogs into conversation instead of switching apps. Read and write roadmaps, OKRs, ideas, and launches through AI. Includes an eval suite for tool selection accuracy
- **[nordic-registry-mcp-server](https://github.com/olgasafonova/nordic-registry-mcp-server)** - Look up companies across Norway, Denmark, Finland, and Sweden through one interface instead of four government websites. Registrations, roles, branches, and annual reports across four countries
- **[gleif-mcp-server](https://github.com/olgasafonova/gleif-mcp-server)** - Validate LEI codes, trace corporate ownership, and cross-reference BIC/ISIN identifiers for KYC and compliance. Look up legal entities by LEI, BIC, ISIN, or name. Built for KYC workflows and regulatory reporting
- **[tilbudstrolden-mcp](https://github.com/olgasafonova/tilbudstrolden-mcp)** - Nordic grocery deal hunter (Denmark, Norway, Sweden). Search live deals across supermarkets, plan weekly dinners around what's cheap, and get shopping lists grouped by store. Ships with 32 starter recipes
- **[ridge](https://github.com/olgasafonova/ridge)** - Reverse-engineer architecture from code (Go, TypeScript, Python) and markdown (Obsidian vaults, doc trees). Builds graphs from static analysis and wiki-links alike. Detects structural drift between git refs so changes don't slip through code review

### Learning Dojos

Spaced repetition trainers with visual metaphors. Built with React, SM-2 scheduling, and too much TypeScript:

- **[Go Dojo](https://olgasafonova.github.io/godojo/)** - Learn Go through 60 quiz cards and gopher illustrations. Every concept gets a visual metaphor: slices become sushi rolls, channels become copper pipes. Six belts, white through black
- **[KanaDojo](https://olgasafonova.github.io/kanadojo/)** - Learn Japanese hiragana and katakana through animated mnemonics, pronunciation audio, and spaced repetition. 92 characters, same belt system

### Libraries & Infrastructure

Go libraries for MCP server developers:

- **[mcp-servercard-go](https://github.com/olgasafonova/mcp-servercard-go)** - Reference implementation of SEP-2127 MCP Server Cards for Go. Drop-in middleware that serves a discovery document at `/.well-known/mcp-server-card` so clients know what your server offers before connecting
- **[mcp-otel-go](https://github.com/olgasafonova/mcp-otel-go)** - OpenTelemetry middleware for go-sdk MCP servers. One function call adds tracing and metrics following the OTel semantic conventions for MCP. Works with Jaeger, Grafana, Datadog, Honeycomb, or any OTLP backend

### Talks & Workshops

- **[techlabs-talk](https://olgasafonova.github.io/techlabs-talk/presentation.html)** (Mar 2026) - "AI That Does Things": talk and live demos for [TechLabs Copenhagen](https://www.techlabs.org/). Covers MCP, compound AI systems, what fails in practice, and how to apply these tools to your own projects.
- **[mcp-workshop](https://olgasafonova.github.io/mcp-workshop/presentation.html)** (Feb 2026) - 1-hour workshop covering what MCPs are, how to use them, and how to build them. Presented for [Women in Product Nordics](https://www.linkedin.com/company/women-in-product-nordics) & [TechWomen Copenhagen](https://www.linkedin.com/company/techwomen-copenhagen). Includes a GLEIF starter kit with platform-specific setup guides.

### Lazgi Hands

- **[lazgi-hands](https://olgasafonova.github.io/lazgi-hands/)** - Interactive visualization teaching Lazgi, a traditional Khorezm dance (UNESCO heritage). Uses algorithms from the birthplace of algorithms.
