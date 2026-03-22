# 🔗 dependencyOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/dependency/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "dependencyoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/dependency/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_asset` | Register an ICT asset (application, database, server, etc.) — Art. 8. |
| `register_function` | Register an ICT-supported business function — Art. 8. |
| `map_dependency` | Create a dependency link between two entities. |
| `dependency_graph` | Get dependency tree for an entity — upstream/downstream. |
| `blast_radius` | Calculate blast radius — what breaks if this entity fails. |
| `spof_analysis` | Detect Single Points of Failure without redundancy. |
| `criticality_score` | Calculate criticality score based on dependencies, classification, redundancy. |
| `asset_inventory` | Full ICT asset inventory with classification and filters. |
| `impact_simulation` | Simulate outage — cascade impact of entity failure. |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

dependencyOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/dependency/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
