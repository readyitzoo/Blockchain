# Voting System

This Voting System is a blockchain-based application designed to ensure secure and transparent voting mechanisms. It utilizes Hardhat, an Ethereum development environment for compiling, deploying, testing, and interacting with smart contracts.

## Getting Started
Follow these instructions to set up and run the project on your local machine for development and testing purposes.

### Prerequisites
Ensure you have Node.js installed on your machine. The project requires Node.js v12.x or later.

```bash
node --version
```
Install Hardhat and other project dependencies:

```bash
npm install
```

### Running the Project

Start the Local Blockchain
Initialize a local Ethereum node using Hardhat:

```bash
npx hardhat node
```

This command starts a local blockchain node, which acts as a test network for deploying and interacting with your smart contract

Deploy Contracts
With the local node running, deploy the contracts by executing:

```bash
npx hardhat run scripts/deploy.js --network localhost
```

This command deploys the VotingSystem contract to your local Ethereum network.

Interact with Contracts
After the deployment, interact with the contracts through:

```bash
npx hardhat run scripts/interact.js --network localhost
```

This script allows you to execute various contract interactions like voting and querying vote results.

Run the Frontend Application
If your project includes a frontend component:

```bash
node app.js
```
This command will start the server for your frontend application, facilitating interactions with the deployed smart contracts.

## Project Structure

- contracts/: Contains the smart contract code written in Solidity.
- scripts/: Scripts for deployment and other contract interactions.
- test/: Tests for the smart contracts.
- app.js: The main file for the frontend application (if applicable).

## Project Members

- <a href="https://readme.com](https://github.com/MihaiMilitaru/" >Militaru Mihai-Alexandru</a>
