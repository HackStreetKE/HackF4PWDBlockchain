

# Blockchain Solution for Hack4Series Hack4PWD Hackathon

## Overview

This project aims to provide a comprehensive solution to address the education, health cover, and upskilling needs of persons with disabilities (PWDs) through creative research and development (R&D). By leveraging Blockchain technology, we ensure the credibility of institutions focused on PWDs, the authenticity of educators upskilling PWDs, and the transparent allocation of funds towards innovative R&D solutions.

## Why Blockchain?

### Credibility of Institutions and Educators

Blockchain offers an immutable record-keeping system, ensuring that the credentials of institutions and educators involved in the upskilling of PWDs are verifiable and tamper-proof. This instills trust and accountability within the ecosystem.

### Facilitating Funds for Creative R&D

Blockchain's transparent and decentralized nature makes it ideal for managing crowdfunding campaigns and financial transactions. By using smart contracts, we can automate the disbursement of funds based on predefined conditions, ensuring that funds are utilized effectively for the intended purposes.


## Solution Architecture

### Components

1. **Smart Contracts**: Written in Solana, these contracts facilitate crowdfunding and execute transactions based on specific conditions.
2. **Immutable Ledger**: Records the credentials of institutions and educators, and tracks the allocation of funds.
3. **User Interface**: Allows stakeholders to interact with the system, verify credentials, and participate in crowdfunding campaigns.

### Implementation

Unfortunately, attempts to use the Azure Blockchain service (Consensys Quorum) encountered errors, likely due to the limited services available with the Azure Student subscription. As a result, we have chosen to implement the smart contracts on Solana.

#### Azure Blockchain Milestone
Successfully completed the Introduction to Blockchain by Azure course in Microsoft Learn where I got to understand the Blockchain services offered and how I can apply my Blockchain skills within the Azure services.

https://learn.microsoft.com/api/achievements/share/en-us/DennisKaruri-0469/YQQPJJSR?sharingId=731DA067057B8A42
## Smart Contract

The smart contract is designed to:

- Facilitate crowdfunding by allowing stakeholders to contribute funds.
- Automatically execute transactions based on conditions such as milestones achieved or R&D outcomes.

## Setting Up the Development Environment

To build on Ethereum, follow these steps:

### Prerequisites

1. **Node.js and npm**: Ensure you have Node.js and npm installed.
2. **Truffle**: Install Truffle, a development environment, testing framework, and asset pipeline for Ethereum.
3. **Ganache**: Install Ganache, a personal blockchain for Ethereum development.
4. **MetaMask**: Set up MetaMask, a browser extension for Ethereum wallet management.
5. **Solidity**: The smart contract programming language.

### Installation

1. **Node.js and npm**: Download and install from [Node.js official website](https://nodejs.org/).
2. **Truffle**: Install via npm:
   ```bash
   npm install -g truffle
   ```
3. **Ganache**: Download and install from [Ganache official website](https://www.trufflesuite.com/ganache).
4. **MetaMask**: Add the MetaMask extension from [MetaMask official website](https://metamask.io/).

### Setting Up

1. **Create a New Truffle Project**:
   ```bash
   truffle init
   ```
2. **Compile and Migrate Smart Contracts**:
   ```bash
   truffle compile
   truffle migrate
   ```
3. **Connect MetaMask to Ganache**:
   - Open Ganache and start a new workspace.
   - In MetaMask, add a new network with the RPC URL pointing to Ganache (typically `http://127.0.0.1:7545`).

### Developing Smart Contracts

Write your smart contracts in the `contracts/` directory and use Truffle to compile and deploy them.

---

This README outlines the project's objectives, the role of Blockchain technology in addressing challenges faced by PWDs and provides a guide for setting up the development environment on Ethereum.
