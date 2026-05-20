# MCP Deprecation Gate Remote MCP

MCP tool deprecation receipt with structured receipts.

Paid remote MCP for MCP tool deprecation receipt, structured receipts, audit logs, and reviewer-ready evidence.

## Public Endpoints

- Website: https://mcpdeprecation.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://mcpdeprecation.clauxel.com/mcp
- Server card: https://mcpdeprecation.clauxel.com/server-card.json
- Registry name: `com.clauxel.mcpdeprecation/mcpdeprecation-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_tool_deprecation`
- `suggest_replacement_tool`
- `issue_deprecation_receipt`
- `sync_tool_registry`
- `export_deprecation_log`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://mcpdeprecation.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://mcpdeprecation.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://mcpdeprecation.clauxel.com/server-card.json
- MCP endpoint: https://mcpdeprecation.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
