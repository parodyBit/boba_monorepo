---
description: A comprehensive guide to use Witnet
---

# Introduction to Wit/Oracle


The Wit/Oracle is a public, permissionless, and fully decentralized Proof-of-Stake blockchain that is powered by its own cryptocurrency, the $WIT coin. Also known as the Witnet blockchain, its primary function lies in efficiently providing public data from the Internet into all sorts of smart-contract capable blockchains and Web3 solutions in a secure, traceable and trustworthy manner.

Because the Wit/Oracle blockchain nodes are cryptoeconomically incentivized to remain honest, we don’t need to trust that they are telling the truth, but rather be certain that it’s in their best interest to do so. The Wit/Oracle is live on 28+ chains, including Boba/ETH and Boba/BNB.

---

## Why Use Witnet on Boba?

- **Easy Access to Real-World Data**: Witnet provides a straightforward way for smart contracts to interact with external data sources. This is crucial for applications that need to process real-world information, like prices, weather reports, or the results of events.
- **Decentralization and Security**: The decentralized nature of Witnet ensures that data is not in control of a single entity, reducing the risks of manipulation or single points of failure. This increases the security and reliability of the applications built on it.
- **Blockchain Agnosticism**: Witnet’s compatibility with multiple blockchain platforms means that builders are not restricted to a single blockchain. This allows for the creation of cross-chain applications and services.
- **Flexibility in Data Sources**: Builders can source data from a variety of external sources, giving them the flexibility to choose the most relevant and reliable data for their applications.
- **Token Incentives for Data Accuracy**: The tokenomics of Witnet incentivize nodes to provide accurate data, as they are rewarded for their honest services and penalized for dishonesty. This mechanism promotes a high level of data integrity.

---
## Wit/Oracle Boba Deployments

| Network              | EVM Artifacts                                                                                                                                                                                                                                                                                          |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Boba ETH/L2**      | [Wit/Oracle](https://bobascan.com/address/0x77703aE126B971c9946d562F41Dd47071dA00777) • [Wit/Price Feeds](https://bobascan.com/address/0x1111AbA2164AcdC6D291b08DfB374280035E1111) • [Wit/Randomness](https://bobascan.com/address/0xC0FFEE98AD1434aCbDB894BbB752e138c1006fAB)                         |
| **Boba BNB/L2**      | [Wit/Oracle](https://bnb.bobascan.com/address/0x77703aE126B971c9946d562F41Dd47071dA00777) • [Wit/Price Feeds](https://bnb.bobascan.com/address/0x1111AbA2164AcdC6D291b08DfB374280035E1111) • [Wit/Randomness](https://bnb.bobascan.com/address/0xC0FFEE98AD1434aCbDB894BbB752e138c1006fAB)             |
| **Boba BNB Testnet** | [Wit/Oracle](https://testnet.bobascan.com/address/0x77703aE126B971c9946d562F41Dd47071dA00777) • [Wit/Price Feeds](https://testnet.bobascan.com/address/0x1111AbA2164AcdC6D291b08DfB374280035E1111) • [Wit/Randomness](https://testnet.bobascan.com/address/0xC0FFEE98AD1434aCbDB894BbB752e138c1006fAB) |
---
## Wit/Oracle Solidity Wizard
The **_Witnet Solidity SDK_** package bundles the **_Solidity Wizard_** tool that will ease the path when trying to programmatically interact with the **_Wit/Oracle blockchain_** from your own smart contracts.

By answering a series of questions, and based on your actual needs, the **_Solidity Wizard_** will create a customized Solidity contract that inherently implements multiple helper methods for either posting data queries to the Wit/Oracle blockchain, estimating minimum required fees, or checking current status of previously posted queries.


The **_Solidity Wizard_** basically covers 4 different use cases:
- Fetch randomness from the Wit/Oracle blockchain.
- Fetch custom data from a set of public data sources on the Internet.
- Fetch custom data from a variable set of public data sources on the Internet.
- Fetch, or force, price updates from a third-party [_WitPriceFeeds_](https://docs.witnet.io/smart-contracts/guides/solidity-contracts/appliances/witnetpricefeeds) instance.

### Run the Solidity Wizard
First, install the **_Witnet Solidity SDK_** package into your project
```bash
$ npm install --save-dev witnet-solidity
$ npx witnet init
```
To run the _Solidity Wizard_ from the CLI, just move to your project's root folder and type:
```bash
$ npx witnet wizard
```
After answering all the questions, a new mock-up contract will be added to the contracts/ folder. You can run the Solidity Wizard and create as many custom contracts as you like.

---
## Resources
- [Website](https://witnet.io)
- [Data Feeds Explorer](https://feeds.witnet.io/boba)
- [Documentation](https://docs.witnet.io/)
- [Community](https://discord.gg/witnet)
- [Wit/Oracle Block Explorer](https://witnet.network)
