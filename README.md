# Blockchain applied to Supply Chains
Simple DEMO for a workshop to demonstrate a simple example of how to integrate supply chain processes on an ETH blockchain.

## Components
* SmartContract that can be deployed on the Ethereum testnet Rinkeby
* Website that connects to metamask and interacts with some funtions of the contract deployed

## Workshop Main Topics
* Blockchains applied to supply chains
* Public / Permissioned / Hydrid blockchain
* Ethereum Overview
* How to interact with Ethereum (testnet Rinkeby)
    * Participants are encouraged to install Metamask on their browser
    * Create a fresh account and explain the mnemonic phrase (public and private keys)
    * Participants will need to get testnet Ethereum and share their public addresses, we can send testnet Ethereum with each other so everybody has some testnet ETH to play with
* Supply chain contract
    * Code, explain and deploy supplychain contract
    * Website
    * All can interact with it
        * Participants can create catches, insert temperatures and buy catches from each other with ETH.
    * Bonus: Do a new contract with some rules that prevent some actions to some participants (To show the example of multiple organizations that dont trust each other and use the blockchain as the base of trust)
## Interact with SmartContract without the website
* Go to [MyEthWallet](https://www.myetherwallet.com/interface/interact-with-contract)
* Connect your Metamask (ex. MEW CX)
* Contract/Interact with Contract
* Input contract address
* Input the ABI (Application Binary Interface) of the contract to interact with
    * This repository has an example contract on the folder "contract" and his respective ABI
* Now you can "Select an item" to choose the function of the contract to interact with

## References
* [Book - Mastering Ethereum](https://github.com/ethereumbook/ethereumbook)
* [Ethereum Components Diagram](https://static.packt-cdn.com/products/9781788831383/graphics/da29eb83-8343-4c0a-8c90-968dc087eb95.png)
* [MyEthWallet](https://www.myetherwallet.com/interface/interact-with-contract)
* [Metamask](https://metamask.io/)
* [Rinkeby (Stats, Explored, Faucet,...)](https://www.rinkeby.io/)
* [Remix](https://remix.ethereum.org/)
* [Ethereum Unit Converter](https://coinguides.org/ethereum-unit-converter-gwei-ether/)