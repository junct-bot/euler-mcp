# Euler MCP Server

MCP server for Euler. Agent-ready API for Euler.

Hosted at [euler.mcp.junct.dev/mcp](https://euler.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "euler": {
      "url": "https://euler.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Euler API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Euler
- **Endpoint:** `https://euler.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [euler.mcp.junct.dev/llms.txt](https://euler.mcp.junct.dev/llms.txt)
- **Server card:** [euler.mcp.junct.dev/.well-known/mcp/server.json](https://euler.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/euler)
- [llms.txt](https://euler.mcp.junct.dev/llms.txt)
- [agents.md](https://euler.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://euler.mcp.junct.dev/openapi.json)

## Keywords

Euler, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
