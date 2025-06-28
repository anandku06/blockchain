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
    3. 