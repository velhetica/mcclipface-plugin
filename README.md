# McClipFace plugin

<img src="assets/logo.png" width="96" alt="McClipFace">

[McClipFace](https://mcclipface.com) is a free coupon and promo code checker for AI shopping assistants. Ask for a coupon, a deal, or let it check for a code before you buy.

This plugin bundles:

- `.mcp.json`: the public McClipFace MCP server (`https://mcclipface.com/mcp`, streamable HTTP, no auth or API key)
- `skills/mcclipface/SKILL.md`: when and how the assistant uses the tools, plus consent and Community Mode rules

## Install

From the xAI plugin marketplace in Grok Build, install **mcclipface**. Or add the MCP server directly to any MCP client:

```json
{ "mcpServers": { "mcclipface": { "type": "http", "url": "https://mcclipface.com/mcp" } } }
```

## Privacy

Lookups send only the store or product name and currency, never cart contents or personal data. Sharing code results is off by default. See the [privacy policy](https://mcclipface.com/privacy.html) and [affiliate disclosure](https://mcclipface.com/affiliate-disclosure.html).

Contact: hello@mcclipface.com

Copyright (c) 2026 GetClippy LLC. All rights reserved.
