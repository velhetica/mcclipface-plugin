# McClipFace plugin

<img src="assets/logo.png" width="96" alt="McClipFace">

[McClipFace](https://mcclipface.com): your assistant checks you're getting the best price before you check out.

When you're about to check out, McClipFace helps your assistant check codes, deals and other stores, then give you one best pick with its total next to where you were headed. It tests codes at checkout when it can, and only keeps a code that lowers the total. It draws on 3,000+ codes across 1,000+ stores, is free and needs no account or API key.

McClipFace may earn a commission on links, at no added cost to you. Commission never changes which pick comes first.

This plugin bundles:

- `.mcp.json`: the public McClipFace MCP server (`https://mcclipface.com/mcp`, streamable HTTP, no auth or API key)
- `skills/mcclipface/SKILL.md`: when and how the assistant uses the tools, plus consent and Community Mode rules

## Install

From the xAI plugin marketplace in Grok Build, install **mcclipface**. Or add the MCP server directly to any MCP client:

```json
{ "mcpServers": { "mcclipface": { "type": "http", "url": "https://mcclipface.com/mcp" } } }
```

## Privacy

Lookups send only the store or product name, the currency, the skill's version and a random install ID (counted only as a monthly-salted hash), never cart contents or personal data. Sharing code results is off by default. See the [privacy policy](https://mcclipface.com/privacy.html) and [affiliate disclosure](https://mcclipface.com/affiliate-disclosure.html).

Contact: hello@mcclipface.com

Copyright (c) 2026 GetClippy LLC. All rights reserved.
