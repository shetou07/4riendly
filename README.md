# 4riendly App

## Introduction
4riendly is a decentralized web application that allows users to place bets on basketball and football pick-up games with their friends. The platform leverages the Solana blockchain to ensure secure, transparent, and automated payouts using smart contracts.

## Features
- Peer-to-peer betting for basketball and football games
- Solana blockchain integration for fast and low-cost transactions
- Secure and automated payouts via smart contracts
- User-friendly React-based interface
- Wallet connection for seamless crypto transactions

## Tech Stack
- **Frontend:** React, Vite
- **Backend:** Node.js (if applicable)
- **Blockchain:** Solana, Solana Playground
- **Smart Contracts:** Rust (Solana programs)
- **CI/CD:** GitLab

## Installation
### Prerequisites
Ensure you have the following installed:
- **Node.js** (latest LTS version)
- **Yarn** or **npm**
- **Solana CLI**
- **Phantom Wallet** (or any Solana-compatible wallet)

### Steps
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd 4riendly
   ```
2. Install dependencies:
   ```sh
   npm install  # or yarn install
   ```
3. Start the development server:
   ```sh
   npm run dev  # or yarn dev
   ```
4. Open your browser and go to `http://localhost:3000`.

## Smart Contract Deployment
1. Set up Solana CLI:
   ```sh
   solana config set --url devnet
   ```
2. Build and deploy the smart contract:
   ```sh
   anchor build
   anchor deploy
   ```
3. Update the contract address in the frontend configuration.

## Usage
- Connect your wallet.
- Create or join a betting pool.
- Confirm the bet with your friend.
- Once the game is over, the winner is declared, and the funds are automatically transferred.

## Contribution
Feel free to open an issue or submit a pull request if you'd like to contribute.

## License
This project is licensed under the MIT License.

