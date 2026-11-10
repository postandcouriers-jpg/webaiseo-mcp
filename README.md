# WebAISEO - AI-search readiness check (MCP server)

**Is your website visible to AI search? Free check, no sign-up, about 5 seconds.**

More people now ask AI assistants instead of searching. WebAISEO checks whether AI search engines can find, read and
trust a web page, gives it a 0-100 score, and lists what to fix, page by page, in priority order.

- **Run the free check in the browser:** https://truetest.uk/ai-search?utm_source=github&utm_medium=readme
- 20 categories, 56 named checks, 19 AI crawlers (robots.txt access, llms.txt, schema / structured data, content
  extractability, citation worthiness, answer-engine readiness and more).

## Connect it to your assistant

Server address: `https://truetest.uk/mcp/ai-search` (remote MCP, streamable HTTP). No account and no sign-in.

In Claude: Settings -> Connectors -> add a custom connector with that address. Other assistants that support remote
MCP servers use the same address.

## The tool

| Tool | What it does | Changes anything? |
|---|---|---|
| `check_ai_readiness` | Checks whether one public web page can be found, read and trusted by AI search engines, and returns the score with the fixes to make. | No. |

## Things you can ask

- "Is https://example.com ready for AI search? What should I fix first?"
- "Can AI crawlers read my pricing page?"

## Free and paid

The readiness check is free. Full-site audits are paid; prices are on https://truetest.uk/ai-search before you buy.
The assistant never buys anything for you.

Help: support@truetest.uk

This repository holds the listing files only (`server.json` for the MCP Registry). The service runs at truetest.uk
(its own home, aiwebsitebuilder.uk, is on the way).

Also from us: **EA Trade Tester** - check a trading robot before you risk money. https://github.com/postandcouriers-jpg/truetest-mcp
