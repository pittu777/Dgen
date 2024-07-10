# DegenToken README
## Overview
DegenToken is an ERC20 token created for Degen Gaming, deployed on the Avalanche network. The token includes functionalities for minting new tokens, transferring tokens, redeeming tokens, checking token balances, and burning tokens.

#### IN VIDEO METAMASK POP-UP NOT SHOWING BUT IN SCREEN IT SHOWED AND I CLICKED ON CONFORM 

LINK - https://www.loom.com/share/e1add397a54f45adb2f58a2476670482?sid=d8dab8cd-c63a-4bae-a299-d9260ae19a1c

## Features

- Minting: Only the contract owner can mint new tokens.
- Transferring: Users can transfer tokens to other addresses.
- Redeeming: Users can redeem their tokens, effectively burning them.
- Burning: Users can burn their tokens to reduce the total supply.
- Balance Checking: Users can check their token balance.
## Requirements
- Solidity ^0.8.9
- OpenZeppelin Contracts
- Avalanche C-Chain Network
- MetaMask
- Remix
## Deployment using Remix

#### Open Remix:

- Go to Remix.
#### Create a New File:

- Click on the "+" icon to create a new file.
- Name the file DegenToken.sol and paste the contract code into this file.
#### Compile the Contract:

- Go to the "Solidity Compiler" tab.
- Select the Solidity compiler version ^0.8.9.
- Click "Compile DegenToken.sol".
- Deploy the Contract:

#### Go to the "Deploy & Run Transactions" tab.
- Select "Injected Web3" as the environment to connect to MetaMask.
- Ensure MetaMask is connected to the Avalanche C-Chain network.
- Select the DegenToken contract from the dropdown.
- Click "Deploy" and confirm the transaction in MetaMask.
## MetaMask Configuration
#### Add Avalanche Network:

- Open MetaMask.
- Click on the network dropdown and select "Custom RPC".
- Enter the following details:
- Network Name: Avalanche Network
- New RPC URL: https://api.avax.network/ext/bc/C/rpc
- Chain ID: 43114
- Symbol: AVAX
- Block Explorer URL: https://snowtrace.io
#### Add DegenToken to MetaMask:

- Open MetaMask.
- Click on "Assets" and then "Add Token".
- Select "Custom Token" and enter the DegenToken contract address.
## Viewing Transactions on Snowtrace
After deploying your contract, you can view transactions and contract details on Snowtrace:

- Go to Snowtrace.
- Enter your contract address in the search bar.
- View the transaction details, token transfers, and other contract interactions.
## Usage

#### Minting Tokens
Only the owner can mint new tokens.

#### Transferring Tokens
Users can transfer tokens to other addresses.

#### Redeeming Tokens
Users can redeem their tokens, effectively burning them.

#### Burning Tokens
Users can burn their tokens to reduce the total supply.

#### Checking Token Balance
Users can check their token balance.

