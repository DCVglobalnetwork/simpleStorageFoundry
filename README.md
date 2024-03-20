## SimpleStorageFoundry project 

What you should be able to accomplish 


***compile your smart contract with Foundry***

  
![Screenshot 2024-03-19 131304](https://github.com/DCVglobalnetwork/simpleStorageFoundry/assets/105791829/0f1e0c7d-3d62-4619-b40d-3b021eb54f5e)

![Screenshot 2024-03-19 131540](https://github.com/DCVglobalnetwork/simpleStorageFoundry/assets/105791829/d0dcb33c-46c6-4435-b4c7-7bdf1e45c67b)

![Screenshot 2024-03-19 133455](https://github.com/DCVglobalnetwork/simpleStorageFoundry/assets/105791829/08a2221f-6fce-4135-b584-c328d26663eb)




***deploy your smart contract on local blockchain anvil***




![Screenshot 2024-03-19 143243](https://github.com/DCVglobalnetwork/simpleStorageFoundry/assets/105791829/e22dbbd4-9066-4c8f-b569-a4738deb1601)

![Screenshot 2024-03-19 143322](https://github.com/DCVglobalnetwork/simpleStorageFoundry/assets/105791829/0f331668-3ee3-4cdf-8605-8693bcd3b4da)

![Screenshot 2024-03-19 150345](https://github.com/DCVglobalnetwork/simpleStorageFoundry/assets/105791829/6858c75e-c011-4ed8-8571-3906763ba2ce)

![Screenshot 2024-03-19 150410](https://github.com/DCVglobalnetwork/simpleStorageFoundry/assets/105791829/97b0e46c-d267-4660-8bdb-cb1fa1a44a1c)


# Important note! 

![Screenshot 2024-03-20 112631](https://github.com/DCVglobalnetwork/simpleStorageFoundry/assets/105791829/164e9235-43f8-40a8-954f-459035d5f2b9)


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

## HAPPY CODING!!!

