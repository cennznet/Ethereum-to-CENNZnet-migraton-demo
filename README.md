# Ethereum to CENNZnet migraton demo

This demo connects to the network thta MetaMask is connected to.

[Live demo](https://ethereum-to-cennz-net-migraton-demo.vercel.app/)

Please connect MetaMask to Rinkeby to use the demo in Ethereum (default)!

To run the CENNZnet contract, you can connect the frontend to the CENNZnet backend by modifying the `contract_address` in /frontend/src/store/index.js

This project is for demonstrating migrating an Ethereum app to CENNZnet.

This is a simple game that uses smart contracts as the backend with a VueJS frontend. It allows the user to mint an NFT for their chosen character and create a transaction to attack the boss. This project adapted from [this Solidity tutorial](https://betterprogramming.pub/create-a-blockchain-game-with-solidity-web3-and-vue-js-c75eed4b49a6).

## Running this project

Once you have deployed the contract to either Ethereum or CENNZnet, you can connect the frontend to it by modifying the `contract_address` in /frontend/src/store/index.js


## Running this project and deploying to Ethereum

To run this project on the Ethereum TestNet Rinkeby:

We'll use Alchemy to access a node, create a free account and get some test tokens to use on Rinkeby using the [Alchemy faucet](https://www.rinkebyfaucet.com/).

* Create an ethereum account and get tokens to use on Rinkeby
* Get your account private key using MetaMask following [this guide](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key)

Compile and deploy the smart contract using the [Remix IDE](https://remix.ethereum.org/).

## Deploying to CENNZnet

To deploy to CENNZnet, simply add CENNZnet to MetaMask and deploy using the [Remix IDE](https://remix.ethereum.org/).


## Notes from the original project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

