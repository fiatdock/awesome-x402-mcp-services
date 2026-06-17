# awesome-x402-mcp-services

Curated list of awesome commercial services that require x402 payments and use MCP. No accounts required. Payments via x402 for MCP tools.

### Table of Contents

- [Search](#search)
- [Finance](#finance)

### Helpful Links

- [x402/MCP Developers](#developers)

## Services

### Search

- [Recall Kitchen](https://recallkitchen.com/docs/#mcp) offers search for product, food, and vehicle recalls.

### Finance

- [FiatDock](https://fiatdock.com) - Non-custodial marketplace where AI agents discover and pay for MCP services per call in USDC via x402 (Base). 3 MCP tools: `search_services`, `get_service`, `call_service` (auto 402→sign→retry). Payments settle directly buyer-wallet → seller-wallet; 1% on-chain split (0% a seller's first 30 days), never custodial. Sellers list free. Also a non-custodial USDC↔bank on/off-ramp. Remote `https://fiatdock.com/mcp` or `npx fiatdock-mcp`.

## Developers

- [xpaysh/awesome-x402](https://github.com/xpaysh/awesome-x402)
   - [Quick Start Guides](https://github.com/xpaysh/awesome-x402?tab=readme-ov-file#-quickstart-guides)
   - [Example Applications](https://github.com/xpaysh/awesome-x402?tab=readme-ov-file#-example-applications)
- [xpaysh/awesome-mcp-monetization](https://github.com/xpaysh/awesome-mcp-monetization)
- [xpaysh/awesome-agentic-economy](https://github.com/xpaysh/awesome-agentic-economy)

## Contributing

To add your commercial service to this curated list (no payment required for submission):

1. Ensure your service requires x402 payments and integrates with MCP.
2. Open a pull request with your service added to the Services section in the format: `- [Service Name](https://link-to-service) - Brief description.`
3. Provide evidence or details on how it uses x402 payments and MCP.
4. Your PR will be reviewed for inclusion.
