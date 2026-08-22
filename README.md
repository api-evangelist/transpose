# Transpose (transpose)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
