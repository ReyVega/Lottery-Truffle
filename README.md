# Lottery-Truffle
## Description
This repo includes the backend for the lottery-application, which is used to deploy smart-contracts within the Ethereum blockchain. The frontend was developed with Next.js, to find the configuration follow the next link: [Lottery](https://github.com/ReyVega/Lottery)

## Technologies used
1. Next.js - Framework used for frontend
2. TypeScript - Programming Language fo frontend
3. Web3.js - Library to manage transactions among betters wihtin Next.js
4. MetaMask - Virtual wallet to hold cryptocurrency
5. Infura - API which connects projects to the Ethereum Blockchain
6. Solidity - Programming Language for smart-contracts
7. Truffle - Framework for deploying smart-contracts

## Important things to take into consideration
1. Create a .env file in the project which contains your Ethereum address and Infura's API Key (Infura Rinkeby)

```
// .env file
PRIVATE_KEY_1=Your Ethereum Address
INFURA_API_KEY=Your Infura's API key
```
2. Metamask is essential since the program is implemented to use it
2. To deploy smart-contracts a small amount of Ethereum is needed, so in the internet there are lot of pages to get Ethereum for Rinkeby's testnet
3. To carry out the transactions, smart-contracts need LINKs which is a type of cryptocurrency, to get them you can go to [ChainLink](https://faucets.chain.link/), after getting them, send those LINKs to the smart-contract's address
4. Install the dependencies

## Deploy smart contract
Run the following command to execute and deploy your smart-contracts

```
truffle migrate --network rinkeby
```
