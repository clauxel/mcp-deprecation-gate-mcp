# Quickstart

MCP Deprecation Gate is a hosted remote MCP for MCP tool deprecation receipt.

## Fast Path

1. Open MCP Deprecation Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://mcpdeprecation.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_tool_deprecation with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://mcpdeprecation.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=mcpdeprecation_public_docs&utm_content=quickstart_home
- https://mcpdeprecation.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=mcpdeprecation_public_docs&utm_content=quickstart_pricing
- https://mcpdeprecation.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=mcpdeprecation_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://mcpdeprecation.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
