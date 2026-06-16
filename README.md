# Routescan (Snowtrace) (snowtrace)

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
