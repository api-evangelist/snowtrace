# Routescan (Snowtrace) (snowtrace)

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

Routescan is the first multichain ecosystem explorer, search, API, and analytics platform for all major EVM chains. Operating as Snowtrace for Avalanche C-Chain, Routescan provides high-speed REST APIs compatible with the Etherscan API format, delivering near real-time access to transactions, token transfers, smart contract data, and event logs across Avalanche C-Chain, Arbitrum, Optimism, Base, and 40+ other EVM networks. A single API key grants multichain access across all indexed chains.

## Tags

- Blockchain
- Explorer
- Avalanche
- EVM
- Multichain
- Web3
- Transactions
- Smart Contracts
- NFTs
- DeFi

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Routescan Etherscan-Compatible Account API

Retrieve address balances, normal and internal transaction histories, ERC-20 token transfers, ERC-721 NFT transfers, ERC-1155 token transfers, and historical balance data by block number for any EVM address across all Routescan-indexed chains.

- **Human URL:** [https://snowtrace.io/documentation/api/etherscan-like/accounts](https://snowtrace.io/documentation/api/etherscan-like/accounts)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- Accounts
- Balances
- Transactions
- ERC-20
- ERC-721
- ERC-1155

#### Properties

- [Documentation](https://snowtrace.io/documentation/api/etherscan-like/accounts)

### Routescan Etherscan-Compatible Block API

Query block rewards and estimated block countdown for specific block numbers on any Routescan-indexed EVM chain.

- **Human URL:** [https://snowtrace.io/documentation](https://snowtrace.io/documentation)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- Blocks
- Block Rewards

#### Properties

- [Documentation](https://snowtrace.io/documentation)

### Routescan Etherscan-Compatible Contract API

Access verified smart contract ABIs, source code, and creation transaction data. Supports contract source code verification via POST with up to 250 verifications per day, and status checking for verification submissions.

- **Human URL:** [https://snowtrace.io/documentation/api/etherscan-like/contracts](https://snowtrace.io/documentation/api/etherscan-like/contracts)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- Contracts
- Smart Contracts
- ABI
- Verification

#### Properties

- [Documentation](https://snowtrace.io/documentation/api/etherscan-like/contracts)

### Routescan Etherscan-Compatible Logs API

Query event logs emitted by smart contracts using filter parameters including address, block range, and up to four indexed topics. Useful for tracking on-chain events in real time.

- **Human URL:** [https://snowtrace.io/documentation](https://snowtrace.io/documentation)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- Logs
- Events
- Smart Contracts

#### Properties

- [Documentation](https://snowtrace.io/documentation)

### Routescan Etherscan-Compatible Token API

Retrieve ERC-20 token supply, token holder information, and token metadata for fungible tokens on Routescan-indexed EVM chains.

- **Human URL:** [https://snowtrace.io/documentation](https://snowtrace.io/documentation)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- Tokens
- ERC-20
- Token Supply

#### Properties

- [Documentation](https://snowtrace.io/documentation)

### Routescan Etherscan-Compatible Stats API

Access network statistics including total AVAX supply, last price, and validator/node count for the Avalanche C-Chain and other supported EVM networks.

- **Human URL:** [https://snowtrace.io/documentation](https://snowtrace.io/documentation)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- Stats
- Network
- Supply

#### Properties

- [Documentation](https://snowtrace.io/documentation)

### Routescan Etherscan-Compatible Transaction API

Check transaction execution status (success or failure) and receipt status for any transaction hash on Routescan-indexed EVM chains.

- **Human URL:** [https://snowtrace.io/documentation](https://snowtrace.io/documentation)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- Transactions
- Status
- Receipts

#### Properties

- [Documentation](https://snowtrace.io/documentation)

### Routescan Geth/Parity Proxy API

Ethereum JSON-RPC compatible proxy endpoints for standard methods including eth_blockNumber, eth_getBlockByNumber, eth_getTransactionByHash, eth_getTransactionReceipt, eth_call, eth_gasPrice, and eth_estimateGas.

- **Human URL:** [https://snowtrace.io/documentation](https://snowtrace.io/documentation)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- RPC
- Proxy
- Ethereum
- JSON-RPC

#### Properties

- [Documentation](https://snowtrace.io/documentation)

### Routescan Nametags API

Retrieve address labels and nametags applied to known wallets, contracts, and entities indexed by Routescan across all supported EVM chains.

- **Human URL:** [https://snowtrace.io/documentation](https://snowtrace.io/documentation)
- **Base URL:** `https://api.routescan.io/v2/network/mainnet/evm/{chainId}/etherscan/api`

#### Tags

- Labels
- Nametags
- Addresses

#### Properties

- [Documentation](https://snowtrace.io/documentation)

## Common Properties

- [OpenAPI](/openapi/openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Portal](https://snowtrace.io/)
- [Documentation](https://snowtrace.io/documentation)
- [Plans](https://snowtrace.io/documentation)
- [Sign Up](https://routescan.io/)
- [Contact](https://snowtrace.io/contactus)
- [Terms of Service](https://snowtrace.io/)
- [Status](https://snowtrace.io/)
- [Plans](/plans/plans.yml)
- [Rate Limits](/rate-limits/rate-limits.yml)
- [Fin Ops](/finops/finops.yml)

## Maintainers

**FN:** Routescan
**URL:** https://routescan.io/
