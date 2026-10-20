# Pauhu MCP

Sourced answers for your agent: it asks, Pauhu answers with the source. Try free, pay per result.

`@pauhu/mcp` connects any MCP client to Pauhu. Each answer comes with its source, so your agent can show where it came from.

## Quick start

Add Pauhu to your MCP client. No key is needed to start.

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

## Try, then pay per result

Without a key the daily try applies. When it is used, the reply says how to continue: a prepaid balance token in `PAUHU_TOKEN`, with the endpoint it names in `PAUHU_MCP_URL`. If you already hold a key, set `PAUHU_TOKEN` to use it from the start. If the service asks for an account, Pauhu prints a sign-in link to open in your browser.

Prices per delivered result: https://api.pauhu.ai/v1/lds/outputs

## Questions and ideas

Ask in [Discussions](../../discussions): setup help in **Q&A**, requests in **Ideas**. Please do not post keys, tokens or personal data.

## Links

- Package: https://www.npmjs.com/package/@pauhu/mcp
- Pauhu AI: https://pauhu.ai
- European data: https://pauhu.eu

## Licence

Apache-2.0, Pauhu AI Ltd.
