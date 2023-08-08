# Uniswap v4 Take Profits Hook

This code is part of a lesson at LearnWeb3 teaching how to build hooks for Uniswap v4. In this example, we build a hook that allows users to place 'take-profit' positions. For example, in an ETH/DAI pool if currently 1 ETH = 1500 DAI, you could place a take-profit order as "sell all my ETH when 1 ETH = 2000 DAI" which will be executed automatically.

This code is inspired from https://github.com/saucepoint/v4-stoploss stop-loss orders, with slight differences.   

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
