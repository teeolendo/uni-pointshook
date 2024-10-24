# Uniswap Points Hook
Using Hooks to distribute token rewards.

## Uniswap v4 Sandbox

**Points Hook**
This is a sandbox repo to test out the use of Hooks on Uniswap v4. Specifically used the `afterSwap` hook and the `afterAddLiquidity` hook to determine the points a referee is entitled. The contract utilizes these hooks to calculate the amount of tokens based on a `zeroForOne` swap.

## Tooling

The project usese Foundry. Run the tests using `forge test`. Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

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
