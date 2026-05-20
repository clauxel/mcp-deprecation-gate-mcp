# MCP Deprecation Gate

MCP Deprecation Gate is a hosted remote MCP for MCP tool deprecation receipt.

This repository is a public documentation project for MCP Deprecation Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://mcpdeprecation.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=mcpdeprecation_public_docs&utm_content=readme_home
- Pricing: https://mcpdeprecation.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=mcpdeprecation_public_docs&utm_content=readme_pricing
- Checkout: https://mcpdeprecation.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=mcpdeprecation_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://mcpdeprecation.clauxel.com/mcp
- Server card: https://mcpdeprecation.clauxel.com/server-card.json
- Registry name: `com.clauxel.mcpdeprecation/mcpdeprecation-mcp`
- Tools: `check_tool_deprecation`, `suggest_replacement_tool`, `issue_deprecation_receipt`, `sync_tool_registry`, `export_deprecation_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_tool_deprecation
- MCP tool: suggest_replacement_tool
- MCP tool: issue_deprecation_receipt
- MCP tool: sync_tool_registry
- MCP tool: export_deprecation_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
