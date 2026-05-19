# netdiag-mcp

Ping, traceroute, DNS lookup, HTTP check, SSL verify, port scan, MTR, WHOIS, and bandwidth test u2014 all from your AI agent. Works offline, no cloud dependency. Your network troubleshooter in a box.

## Quick Start

```bash
git clone https://github.com/marilynceo/netdiag-mcp.git
cd netdiag-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://netdiag.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/netdiag-mcp

# Or connect directly via MCP client
# Endpoint: https://netdiag.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
