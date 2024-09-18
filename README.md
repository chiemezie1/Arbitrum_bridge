# ETH Bridging with Arbitrum SDK

This project demonstrates how to bridge ETH from Ethereum Sepolia to Arbitrum Sepolia using the Arbitrum SDK and ethers.js.

## Prerequisites

- Node.js (v14 or later recommended)
- `npm` or `yarn` for package management
- Access to Ethereum Sepolia and Arbitrum Sepolia networks
- A `.env` file with the necessary environment variables

## Setup

1. **Clone the Repository**

```bash
    git clone https://github.com/chiemezie1/Arbitrum_bridge
    cd Arbitrum_bridge
```
## Install Dependencies
Ensure you have npm or yarn installed, then run:

```bash
npm install
```
### or

```bash
yarn install
```
## Configure Environment Variables

Create a .env file in the root directory of the project and add the following environment variables:

```
L1RPC=https://your-ethereum-sepolia-rpc-url
L2RPC=https://your-arbitrum-sepolia-rpc-url
PRIVATE_KEY=your-private-key
```

* L1RPC: The RPC URL for Ethereum Sepolia.
* L2RPC: The RPC URL for Arbitrum Sepolia.
* PRIVATE_KEY: Your Ethereum private key used for signing transactions.

## Usage
Run the Script
Execute the script to deposit ETH from Ethereum Sepolia to Arbitrum Sepolia:

npm start
### or
```
yarn start
```
The script will:

- Initialize providers for both Ethereum and Arbitrum Sepolia networks.
- Deposit 0.005 ETH from Ethereum Sepolia to Arbitrum Sepolia.
- Wait for the transaction to be mined on both Ethereum and Arbitrum networks.
- Log the status of the deposit and the new balance on Arbitrum.

# Contributing
Feel free to open issues or submit pull requests if you find any bugs or have improvements to suggest.