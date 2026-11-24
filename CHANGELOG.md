# Changelog

## 0.3.1 — 2026-11-25

First release: a Claude Desktop extension (`otterbridge-shopee-mcp.mcpb`), a Claude Code
plugin, and a plain stdio server for any other MCP client. 32 tools and 3 prompts.

### Added

- **Connect a shop** with your own Shopee developer app: request signing, seller
  authorization caught on `localhost`, tokens saved and refreshed by themselves, several
  shops at once.
- **Preview, then apply.** Every tool that changes the shop returns a preview and a
  `plan_id`; `shopee_apply_plan` is the only tool that carries out a change. Plans run once
  and expire after 30 minutes. Read-only mode leaves out applying altogether.
- **Products:** bulk create from rows (`parent_sku` groups variations; category,
  attributes and brand by name; images from files or URLs; re-runs skip SKUs already in
  the shop), export, price / stock / details / status changes by rows or by rule
  (percent, amount, rounding, price endings, stock delta), delete, variations, reviews and
  replies, boosts.
- **Orders and shipping:** orders for any date range; ship every order waiting
  (pickup or drop-off chosen per package); airway bill PDFs per courier, using Shopee's new
  job-based label flow with the older flow as a fallback.
- **Returns:** list requests with their deadlines; accept, offer refund-only or
  return-and-refund, accept a counter-offer, or dispute with evidence.
- **Reports:** catalogue and stock, sales, payouts and fees (including Vietnam's SPayLater
  fee, and profit when you give unit costs), shop health, listing quality.
- **Every other endpoint:** a bundled catalogue of all 454 Shopee Open API v2 endpoints,
  with search, parameter docs, and calls by name (`shopee_api_read` / `shopee_api_write`).
- **Prompts:** daily briefing, new listing, pricing review.
- Follows Shopee's notices up to November 2026: `get_shipment_list` for orders waiting to
  ship, Shopee's "results might be outdated" campaign warning passed on, and
  `default_model_id` in product exports.

### Notes

- Credentials for Claude Code and other clients can live in `~/.shopee-mcp/.env`.
- Shipping, airway bills and returns are not yet tested end to end: Shopee's sandbox
  can't create test orders for Malaysian test shops at the moment, and doesn't support
  returns. See *Known limitations* in the README.
