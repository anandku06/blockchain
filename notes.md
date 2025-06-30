## Smart Contracts

- a set of instructions executed in a decentralised way without the need for a centralised or third party intermediary
- used on smart contracts platforms or blockchains like Ethereum
- NOTE : Bitcoin is intentionally *turning incomplete*

## Oracles

- A blockchain oracle connects blockchains to external data or systems. 
- Since smart contracts operate in closed environments and can’t access information outside their chain, oracles act as trusted messengers that bring in real-world data or send on-chain data out.


## The Oracle Problem

- a fundamental challenge in blockchain systems: smart contracts can’t access off-chain data on their own.
    1. **Root cause**: Blockchains are deterministic. All nodes must reach identical conclusions from the same data. 
        Without oracles, smart contracts risk inconsistencies.
    2. **Tradeoff** : This ensures security and consensus but isolates blockchains from external data.
    3. **Why It Matters** : Many use cases, especially in decentralized finance (DeFi), gaming, and insurance, depend on real-world information.
    4. **The Oracle Challenge** : Oracles bridge this gap, but they introduce trust assumptions. While blockchains are designed to be trustless, oracles must be trusted to deliver accurate, tamper-resistant data.
    5. **Decentralized solution** : Modern oracles solve this by distributing trust across multiple nodes without compromising decentralization.

## DONs

- Decentralized Oracle Networks
- distribute data tasks across multiple independent nodes, reducing reliance on a single oracle. 
- These nodes operate in a peer-to-peer network, verifying off-chain data and reaching consensus before delivering it to smart contracts.

## Hybrid Smart Contracts

- on-chain agreements and off-chain agreements together makes a hybrid smart contract

## Chainlink

- a modular DON that can both bring external data and external computation into the smart contracts to make sure they're decentralized end to end.
- allows for us to get data, do upkeeps, get random numbers, or really customise smart contracts in a meaningful way
- blockchain agnostic

## L2 (Layered-2)

- solves an issue that most blockchains see where they don't scale very well,
- solves scalability issues
- two types of true layer 2s:
    1. Optimistic Rollups : Arbitrum and Optimism
    2. Zero-knowledge rollups : ZK Sync and Polygon ZK EVM

## Web1
    - permissionless open-sourced web with static content

## Web2
    - permissioned web, with dynamic content, where companies run your agreements on thier servers

## Web3
    - permissionless web, with dynamic content, where decentralized censorship resistant networks run your agreement and code. It generally is accompanied by the idea of user owned ecosystems, where the protocols you interact with you also own a portion of, instead of solely being the product. 