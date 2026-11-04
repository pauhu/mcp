# Pauhu MCP

Sourced answers for your agent: it asks, Pauhu answers with the source. Tools run with an authorized key.

`@pauhu/mcp` connects any MCP client to Pauhu. Each answer comes with its source, so your agent can show where it came from.

## Quick start

Add Pauhu to your MCP client.

```json
{
  "mcpServers": {
    "pauhu": { "command": "npx", "args": ["-y", "@pauhu/mcp"] }
  }
}
```

Ready-made configs for common clients are in [`examples/`](examples/):

| Client | File | Where it goes |
| --- | --- | --- |
| Cursor | [`cursor-mcp.json`](examples/cursor-mcp.json) | `~/.cursor/mcp.json` or `.cursor/mcp.json` in a project |
| VS Code | [`vscode-mcp.json`](examples/vscode-mcp.json) | `.vscode/mcp.json` in a project |
| Other desktop clients | [`mcp-servers.json`](examples/mcp-servers.json) | the client's MCP config file (`mcpServers` format) |

Needs Node.js 18 or newer.

## Keys and price

If you already have an authorized key, set `PAUHU_TOKEN`. Otherwise start the connector; if sign-in is required, it prints a link to open in your browser. An authorized key is required to use tools.

The price shows when payments open.

## Questions, problems and ideas

Ask in [Discussions](../../discussions): setup help in **Q&A**. Report a wrong page, a connector problem or an idea in [Issues](../../issues/new/choose). Agents are welcome: see [AGENTS.md](AGENTS.md). More in [CONTRIBUTING.md](CONTRIBUTING.md), and for vulnerabilities [SECURITY.md](SECURITY.md).

Please do not post keys, tokens or personal data.

## Links

- Package: https://www.npmjs.com/package/@pauhu/mcp
- Pauhu AI: https://pauhu.ai
- European data: https://pauhu.eu
- Developers: https://pauhu.dev
- Pauhu: https://pauhu.com
- Community (Pauhu Insiders): https://discord.gg/tCBF5swNbV

## Licence

Apache-2.0, Pauhu AI Ltd.
