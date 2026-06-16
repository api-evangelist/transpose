# Transpose (transpose)

Historical blockchain data REST API providing access to transaction history, token transfers, NFT metadata, smart contract events, DEX swaps, and price data across Ethereum and other EVM-compatible chains. Offers five enterprise-grade REST APIs plus a SQL Analytics API for querying indexed blockchain data across Ethereum, Polygon, Optimism, Base, Arbitrum, Avalanche, BSC, Bitcoin, and Tron.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/transpose/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/transpose/refs/heads/main/apis.yml)

## Tags

- Blockchain
- NFT
- Cryptocurrency
- Web3
- Ethereum
- Token Transfers
- Smart Contracts
- Historical Data
- DeFi
- DEX

## Timestamps

- **Created:** 2026-06-14
- **Modified:** 2026-06-14

## APIs

### Transpose Block API

Provides access to low-level blockchain primitives including accounts, blocks, transactions, logs, and traces across supported EVM chains. Enables bulk retrieval of raw settlement-layer data for analytics and indexing use cases.

- **Human URL:** [https://docs.transpose.io/](https://docs.transpose.io/)
- **Base URL:** `https://api.transpose.io`

#### Tags

- Blockchain
- Blocks
- Transactions
- Logs
- Accounts

#### Properties

- [Documentation](https://docs.transpose.io/)
- [OpenAPI](https://docs.transpose.io/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Transpose Token API

Retrieves any token balance, mint, transfer, or burn across ERC-20, ERC-777, and native tokens. Supports historical token transfers, DEX swap queries, and native token transactions across multiple EVM chains including Ethereum, Polygon, and Arbitrum.

- **Human URL:** [https://docs.transpose.io/verified-endpoints/token-api/overview/](https://docs.transpose.io/verified-endpoints/token-api/overview/)
- **Base URL:** `https://api.transpose.io`

#### Tags

- Tokens
- ERC-20
- Token Transfers
- DEX
- Swaps
- Balances

#### Properties

- [Documentation](https://docs.transpose.io/verified-endpoints/token-api/overview/)
- [OpenAPI](https://docs.transpose.io/verified-endpoints/token-api/overview/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Transpose NFT API

Provides a complete view of NFT sales, activity, balances, collections, ownership histories, and transfers spanning all NFT exchanges, collections, and standards including ERC-721 and ERC-1155. Supports Ethereum, Polygon, Optimism, Scroll, Arbitrum, Base, and Avalanche chains.

- **Human URL:** [https://docs.transpose.io/verified-endpoints/nft-api/routes/transfers/](https://docs.transpose.io/verified-endpoints/nft-api/routes/transfers/)
- **Base URL:** `https://api.transpose.io`

#### Tags

- NFT
- ERC-721
- ERC-1155
- Collections
- Transfers
- Sales
- Ownership

#### Properties

- [Documentation](https://docs.transpose.io/)
- [OpenAPI](https://docs.transpose.io/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Transpose ENS API

Provides access to Ethereum Name Service records and transfer history, enabling lookup of ENS domain ownership, resolution records, and historical ENS activity on Ethereum.

- **Human URL:** [https://docs.transpose.io/](https://docs.transpose.io/)
- **Base URL:** `https://api.transpose.io`

#### Tags

- ENS
- Ethereum Name Service
- Domains
- Identity

#### Properties

- [Documentation](https://docs.transpose.io/)
- [OpenAPI](https://docs.transpose.io/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Transpose Token Prices API

Delivers real-time and historical OHLC price data for any token including LP tokens since genesis. Supports minute-to-month granularity for price series, candlestick analysis, and LP token valuation across Balancer, Curve Finance, Uniswap, Convex Finance, Yearn, Synthetix, and Aave.

- **Human URL:** [https://docs.transpose.io/verified-endpoints/token-prices-api/overview/](https://docs.transpose.io/verified-endpoints/token-prices-api/overview/)
- **Base URL:** `https://api.transpose.io`

#### Tags

- Token Prices
- OHLC
- Historical Prices
- DeFi
- LP Tokens

#### Properties

- [Documentation](https://docs.transpose.io/verified-endpoints/token-prices-api/overview/)
- [OpenAPI](https://docs.transpose.io/verified-endpoints/token-prices-api/overview/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Transpose SQL Analytics API

Custom SQL query interface against Transpose's indexed blockchain data. Accepts POST requests with SQL queries to enable flexible, ad-hoc analysis of blockchain data across all supported chains and data layers including settlement, asset, and protocol layers.

- **Human URL:** [https://docs.transpose.io/](https://docs.transpose.io/)
- **Base URL:** `https://api.transpose.io`

#### Tags

- SQL
- Analytics
- Custom Queries
- Blockchain Data

#### Properties

- [Documentation](https://docs.transpose.io/)
- [OpenAPI](https://docs.transpose.io/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Portal](https://app.transpose.io)
- [Documentation](https://docs.transpose.io/)
- [Quickstart](https://docs.transpose.io/quickstart/)
- [Pricing](https://www.transpose.io/pricing)
- [Blog](https://www.transpose.io/blogs)
- [Authentication](https://docs.transpose.io/quickstart/)
- [Plans](plans/plans.yml)
- [Rate Limits](rate-limits/rate-limits.yml)
- [Fin Ops](finops/finops.yml)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
