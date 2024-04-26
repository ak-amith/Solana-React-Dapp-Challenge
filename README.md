# Solana Phantom Wallet Integration

This is a basic React application showcasing integration with the Solana blockchain via the Phantom wallet provider. The application enables users to create wallets, link to existing ones, transfer SOL tokens, and monitor wallet balances.

## Table of Contents

- [Getting Started](#getting-started)
- [Features](#features)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Getting Started

To launch the application locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install the necessary dependencies using: npm install
4. Start the development server with: npm start
5. Open your preferred browser and visit: http://localhost:3000

## Features

- Generate a new Solana account.
- Establish a connection with an existing Phantom wallet.
- Request an airdrop of SOL tokens.
- Transfer SOL tokens to linked wallets.
- Check wallet balances.

## Dependencies

This project relies on the following technologies and libraries:

- [React](https://reactjs.org/)
- [Solana Web3.js](https://solana-labs.github.io/solana-web3.js/)
- [Phantom Wallet](https://www.phantom.app/)

## Usage

1. *Create a New Solana Account:*
   Click the "Create a New Solana Account" button to generate a new account, request an airdrop of SOL tokens, and display the created wallet's details.

2. *Connect Wallet:*
   Use the "Connect Wallet" button to link to an existing Phantom wallet. Once connected, you'll be able to transfer tokens and view balances.

3. *Transfer SOL to New Account:*
   After creating a new account or linking a wallet, utilize the "Transfer SOL to New Account" button to send SOL tokens to the new account.

4. *Get Wallet Balance:*
   Click the "Get Wallet Balance" button to check the balance of the currently connected wallet or the newly created account.


