- 👋 Hi, I’m Vidhi Jitendra Jogeshwar. I am an Agile Coach, Scrum Master, EDI Specialist for SAP OTC processes and SAP Techno-Functional consultant with specialization in SD processes. A
- 👀 I’m interested in becoming a Block Chain Developer.
- 🌱 I’m currently learning Block Chain development.
- 💞️ I’m looking to collaborate on Block Chain projects
- 📫 How to reach me - Email ID : vidhi.jogeshwar@gmail.com

# Table of Contents
- [Table of Contents](#table-of-contents)
- [Resources For This Course](#resources-for-this-course)
- [Lesson 0: Welcome To Blockchain](#lesson-0-welcome-to-blockchain)
  - [What is a Blockchain?](#what-is-a-blockchain)
  - [Making Your First Transaction](#making-your-first-transaction)
  - [How Do Blockchains Work?](#how-do-blockchains-work)
    - [Consensus](#consensus)
  - [The Future](#the-future)
  - [Miscellaneous](#miscellaneous)
- [Lesson 1: Welcome to Remix! Simple Storage](#lesson-1-welcome-to-remix-simple-storage)
    - [Everything in this section can be read about in the Solidity Documentation](#everything-in-this-section-can-be-read-about-in-the-solidity-documentation)
    - [Remix](#remix)
    - [Basic Solidity](#basic-solidity)
    - [Deploying to a "Live" network](#deploying-to-a-live-network)
- [Lesson 2: Storage Factory](#lesson-2-storage-factory)
    - [Inheritance, Factory Pattern, and Interacting with External Contracts](#inheritance-factory-pattern-and-interacting-with-external-contracts)
- [Lesson 3: Fund Me](#lesson-3-fund-me)
    - [Payable, msg.sender, msg.value, Units of Measure](#payable-msgsender-msgvalue-units-of-measure)
    - [Chainlink Oracles](#chainlink-oracles)
    - [Importing from NPM and Advanced Solidity](#importing-from-npm-and-advanced-solidity)


# Resources For This Course
- [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)
- [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/)
- [Hybrid Smart Contracts](https://blog.chain.link/hybrid-smart-contracts-explained/)
- [Blockchain Oracles](https://betterprogramming.pub/what-is-a-blockchain-oracle-f5ccab8dbd72?source=friends_link&sk=d921a38466df8a9176ed8dd767d8c77d)
- [What is a blockchain](https://www.investopedia.com/terms/b/blockchain.asp)
# Lesson 0: Welcome To Blockchain
## What is a Blockchain?
- [Learning Blockchain Day 1](https://github.com/Vjogeshwar/Learning-Blockchain/blob/Block-Chain-Project/Learning%20Block%20Chain%20Day%201%20-%20Theory)
- [Learning Blockchain Day 2](https://github.com/Vjogeshwar/Learning-Blockchain/commit/9ba807ce25387134e68d6c6893f2a46badebdaad)
- ![Day 2 Notes](https://github.com/Vjogeshwar/Learning-Blockchain/blob/Block-Chain-Project/day2-1.PNG)
## Making Your First Transaction
- [Metamask](https://metamask.io/)
- [Etherscan](https://etherscan.io/)
- [Rinkeby Etherscan](https://rinkeby.etherscan.io/)
- [Kovan Etherscan](https://kovan.etherscan.io/)
- Rinkeby Faucet (Check the [link token contracts page](https://docs.chain.link/docs/link-token-contracts/#rinkeby))
- NOTE: The Chainlink documentation always has the most up to date faucets on their [link token contracts page](https://docs.chain.link/docs/link-token-contracts/#rinkeby). If the faucet above is broken, check the chainlink documentation for the most up to date faucet.  
- OR, use the [Kovan ETH Faucet](https://faucets.chain.link/), just be sure to swap your metamask to kovan!
- [Gas and Gas Fees](https://ethereum.org/en/developers/docs/gas/)
- [Wei, Gwei, and Ether Converter](https://eth-converter.com/)
- [ETH Gas Station](https://ethgasstation.info/)

# Lesson 1: Welcome to Remix! Simple Storage
💻 Code: https://github.com/Vjogeshwar/People_List_SmartContract
### [Remix](https://remix.ethereum.org/)
### Basic Solidity
- Versioning
- Compiling
- Contract Declaration
- [Types & Declaring Variables](https://docs.soliditylang.org/en/v0.8.6/types.html)
  - `uint256`, `int256`, `bool`, `string`, `address`, `bytes32`
- Default Initializations
- Comments
- Functions
- Deploying a Contract
- Calling a public state-changing Function
- [Visibility](https://docs.soliditylang.org/en/v0.7.3/contracts.html#visibility-and-getters)
- Scope
- View & Pure Functions
- Structs
- Intro to Storage
- Arrays - Dynamic & Fixed sized
- Compiler Errors and Warnings
- Memory
- Mappings
- SPDX License
- Recap
### Deploying to a "Live" network
- A testnet or mainnet
- [Find a faucet here](https://docs.chain.link/docs/link-token-contracts/#rinkeby)
- Connecting Metamask
- Interacting with Deployed Contracts
- The EVM
# Lesson 2: [Storage Factory]
💻 Code: https://github.com/Vjogeshwar/Inheritance_calling_contract
### Inheritance, Factory Pattern, and Interacting with External Contracts
- Factory Pattern
- Imports
- Deploy a Contract From a Contract
- Interact With a Deployed Contract
- Recap
# Lesson 3: Fund Me
💻 Code: https://github.com/Vjogeshwar/Inheritance_calling_contract
### Payable, msg.sender, msg.value, Units of Measure
- Payable
- [Wei/Gwei/Eth Converter](https://eth-converter.com/)
- msg.sender & msg.value
### Chainlink Oracles
- Decentralized Oracle Network Chainlink
  - Blockchains can't make API calls
  - Centralized Nodes are Points of Failure
- [data.chain.link](https://data.chain.link/)
- Getting External Data with Chainlink Oracles
  - [Chainlink](https://docs.chain.link/)
  - [Faucets and Contract Addresses](https://docs.chain.link/docs/link-token-contracts/)
    - [Kovan](https://docs.chain.link/docs/link-token-contracts/#kovan)
  - [Getting Price Information](https://docs.chain.link/docs/get-the-latest-price/)
### Importing from NPM and Advanced Solidity
- Decimals/Floating Point Numbers in Solidity
- latestRoundData
- Importing from NPM  in Remix
- Interfaces
  - Introduction to ABIs
- [Getting Price Feed Addresses](https://docs.chain.link/docs/reference-contracts/)
- getPrice
- Tuples
  - Unused Tuple Variables
- Matching Units (WEI/GWEI/ETH)
- getConversionRate
- Matching Units (Continued)
- SafeMath & Integer Overflow
  - using keyword
  - [Libraries](https://docs.soliditylang.org/en/v0.8.6/contracts.html#libraries)
  - SafeMath PSA
- Setting a Threshold
- Require
- Revert
- Withdraw Function 
- Transfer
- Balance
- this
- Contract Owners
- Constructor
- ==
- Modifiers
- Resetting
- for loop
- Array Length
- Forcing a Transaction
- Recap
