# mcp-registry

Curated registry of trusted MCP servers Suraya operators can connect to from Cowork-in-Suraya and agent surfaces.

H1 (v1.3 §6.5). MIT-licensed.

> **Sandbox note.** Lives in the suraya meta repo at `apps/mcp-registry/` until `surayainc/mcp-registry` is created. The registry JSON is consumed by the portal at runtime to populate `/portal/admin/mcp-registry`.

## Source of truth

- `registry.json` — the curated entries. Schema documented inline.
- `categories.json` — taxonomy of categories with descriptions.

## Editorial bar

Entries must:
- Have a public canonical source (GitHub repo, official package, etc.)
- Be MCP-standard compliant
- Have at least one operator's first-hand experience documented as a brain observation OR be on the Anthropic-blessed list

Updates ship as PRs against this directory. Each entry gets reviewed for accuracy + tier (`trusted` / `experimental` / `deprecated`).

## v0 scope

Seed list of ~25 servers across categories. Tier-N+ operators can also register custom servers per-tenant via `/portal/admin/mcp-registry` (H2 — not yet shipped).
