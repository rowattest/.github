# RowAttest

Signed proof that strangers can't read your users' data.

RowAttest runs an eight-stage isolation test against your staging Supabase and issues a signed attestation anyone can verify. Free to start; API and MCP included.

- Website: https://rowattest.com
- Create a free account: https://app.rowattest.com/signup
- Verify a report: https://rowattest.com/verify
- REST API: https://app.rowattest.com/api/v1 (keys from the API keys page in the app)
- MCP for Claude Code: `claude mcp add --transport http rowattest https://app.rowattest.com/mcp --header "Authorization: Bearer rak_your_key"`
- Security reports: see SECURITY.md

A product of RW Digital Ventures LLC.
