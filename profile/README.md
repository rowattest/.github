# RowAttest

Signed proof that strangers can't read your users' data.

RowAttest runs an eight-stage isolation test against your staging Supabase project, as signed-in test users it creates and as an anonymous visitor holding only the public anon key, and signs what it finds. Every report is an Ed25519 signed JSON document that anyone can verify at https://rowattest.com/verify. Free to start; API and MCP included.

- Website: https://rowattest.com
- How it works: https://rowattest.com/methodology
- Proof runs against public Supabase starter kits: https://rowattest.com/proof (reports in rowattest/proof-runs)
- Create a free account: https://app.rowattest.com/signup
- Verify a report: https://rowattest.com/verify
- Verify offline and gate CI on a report: https://github.com/rowattest/gate (rowattest-gate 0.1.0, one file, Node 20 or newer, MIT)
- REST API: https://app.rowattest.com/api/v1 (keys from the API keys page in the app; description at https://app.rowattest.com/api/v1/openapi.json)
- MCP server: https://rowattest.com/mcp, or `claude mcp add --transport http rowattest https://app.rowattest.com/mcp --header "Authorization: Bearer rak_your_key"`
- For AI agents, the handshake to check an app's published attestation: https://rowattest.com/agents
- Security reports: see SECURITY.md or email info@rowattest.com

A product of RW Digital Ventures LLC.
