# Ethereum Resources
Some nodes from the presentation. The commands are base on the virtual machine we have provided.

## Glossary
* Truffle : Build & Deploy Tool for Solidity
* Ganache : Simulate a Blockchain on your machine
* Smart Contract == `classes`
* Deploy a smart contract to a Blockchain == `new Object()`\\The deployed Address of the smart Contract is like the instance of the smart contract


## Commands 
Create a new project
```bash
>truffle init
```

(Re)Build and deploy a smart contract
```bash
truffle migrate --reset --all --network development
```

Test the deployment
```bash
>truffle test --network development
```

## Solidity
* [Language Guide](http://solidity.readthedocs.io/en/v0.4.24/)
* Online IDE [Remix](https://remix.ethereum.org)

## Wallet
* [Meta Mask](https://metamask.io)


## Ethereum Test Network Rinkeby
* Get some test ether: [faucet.rinkeby.io](https://faucet.rinkeby.io)
* Blockchain Interaction: [etherscan](https://rinkeby.etherscan.io)