# Metasell AI

The `metasell` MCP server gives read-only access to one Metasell business that the user connected:
calls and call analysis, CRM leads, contacts and tasks, manager performance, alerts and daily summaries.

- Nothing can be created, changed or deleted through it, and call transcripts are not available.
- A sales manager sees only their own calls, leads and tasks.
- Dates are in the business time zone.
- If a tool says the connection is no longer active, ask the user to run `/mcp auth metasell` again.
