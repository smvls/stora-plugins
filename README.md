# Stora

Turn app search data into your next growth move. Ask what changed in your app's visibility, which relevant searches competitors win, or where Apple Ads spend went.

Stora connects your AI assistant to the workspace you choose at [stora.rocks](https://stora.rocks). This package contains connection settings and skills; the hosted MCP server and customer data are not distributed in this repository.

## Connect

Install the plugin in your supported host and follow **Connect Stora**. Sign in to Stora, select a workspace and choose its access. Read access is sufficient for reports. Tracking, drafts and experiment notes require write access. App deletion and imports require an administrator grant. Revoke connections in Stora **Settings → Connected apps**.

For a remote connector, use `https://stora.rocks/mcp` with OAuth. Existing API keys also work for clients that explicitly support them; do not put a key into this repository, a URL or a chat message.

## Claude Code

```text
/plugin marketplace add smvls/stora-plugins
/plugin install stora@stora-plugins
```

Claude's Directory listing becomes available after review. A public repository is an installation source, not proof of Directory approval.

## ChatGPT and Codex

The root `plugin.json` and `mcp.json` use the portable Agent Plugins format. A public directory listing becomes available after OpenAI review. The `.claude-plugin` and `.mcp.json` files provide Claude compatibility for the same package.

## Example requests

- “Review my app's Apple US search visibility this week.”
- “Which relevant searches do direct competitors win?”
- “Track these three terms in Google Play GB, preserving current markets.”
- “Prepare a subtitle experiment and save it as a draft.”
- “Explain the visible and hidden query coverage in my Apple Ads report.”

Reports identify their app, store, market, dates and evidence gaps. Stora can manage its own tracking, drafts and experiment ledger. It cannot publish store listings, change ad campaigns or process purchases.

[Support](https://stora.rocks/support) · [Privacy](https://stora.rocks/privacy) · [Terms](https://stora.rocks/terms)

The package instructions and configuration are MIT licensed. The Stora name and logo identify the service and remain trademarks of their owner.
