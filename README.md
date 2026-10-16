# Metasell AI for Gemini CLI

Ask Gemini CLI about your sales team in plain words, using your own [Metasell](https://metasell.ai) data:
how many calls the team made yesterday, which manager's call scores dropped this week, which leads are
stuck in a stage, or what each manager should improve.

The connection is **read-only**: it cannot create, change or delete anything, and call transcripts are
not shared. You sign in with your Metasell account and choose one business.

## Install

```bash
gemini extensions install https://github.com/Usmon-Muxammad/metasell-ai-gemini
```

Then start Gemini CLI and sign in:

```text
/mcp auth metasell
```

A browser window opens the Metasell sign-in page. Sign in, choose the business and click **Allow access**.

## Try

- "How many calls did my team make yesterday, and what was the average call score?"
- "Which manager had the lowest call scores this week, and what should they work on?"
- "Which leads have been stuck in the same pipeline stage the longest?"
- "Give me today's daily summary for the sales team."

## What it can read

Calls and call analysis, CRM leads, contacts and tasks, manager performance, alerts and daily summaries
for the one business you chose, with your own access rights. A sales manager sees only their own data.

## Disconnect

In Metasell open **Settings → Profile → Connected AI apps** and click **Disconnect**, or run
`gemini extensions uninstall metasell-ai`.

## Links

- Setup guide: https://metasell.ai/en/ai-apps
- Privacy policy: https://metasell.ai/en/privacy
- Terms: https://metasell.ai/en/terms
- Support: main@metasell.ai

The MCP server is `https://mcp.metasell.ai/mcp` (OAuth 2.1 with dynamic client registration).

© Metasell MCHJ
