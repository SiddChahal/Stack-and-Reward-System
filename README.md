# StakingDappYT - Smart Contract & DApp Instructions

Welcome to the StakingDappYT project! This repository contains instructions for interacting with the smart contracts and deploying the DApp.

## Overview of Staking DApp

The StakingDappYT is a decentralized application that enables users to stake ERC20 tokens into the platform and earn rewards. The staking process generates reward tokens per second, rewarding users based on their staked amount and duration. 
[Stakind Dapp Tutorial (Hindi) ](https://www.youtube.com/@CodeEater21)

### Key Tokens

- **Stake Token:** This ERC20 token is used for staking within the DApp. Users need to approve this token for the staking contract before staking.
  
- **Reward Token:** Another ERC20 token generated by the staking process per second. Users earn these tokens as rewards for staking their stake tokens.

## How the Staking DApp Works

1. **Stake Tokens:**
   - Users approve a certain amount of stake tokens to be staked within the DApp by interacting with the staking smart contract.

2. **Generate Reward Tokens:**
   - Once the stake tokens are staked, the smart contract generates reward tokens per second based on the staked amount.

3. **Accumulate Rewards:**
   - Users accumulate reward tokens over time as they keep their stake tokens staked within the DApp.

4. **Claim Rewards:**
   - Users can claim their accumulated rewards by interacting with the smart contract using the `getReward()` function.

5. **Unstake Tokens:**
   - After a staking period or at any point, users can unstake their tokens using the appropriate function in the DApp to retrieve their staked tokens along with the accumulated rewards.

## Smart Contract Instructions

### 1) Approve Stake Token
Before using the `stake()` function, ensure that you approve the stake token to the staking contract.

### 2) Transfer Reward Token
Before using the `getReward()` function, transfer the reward token to the staking contract.

## Smart Contract Instructions

### 1) Approve Stake Token
Before using the `stake()` function, ensure that you approve the stake token to the staking contract.

### 2) Transfer Reward Token
Before using the `getReward()` function, transfer the reward token to the staking contract.

## DApp Instructions

### Prerequisites
- **Metamask:** Install Metamask to access the DApp.

### Steps to Deploy Smart Contracts on Sepolia
1. Deploy the staking, stake token, and reward token smart contracts on Sepolia.
   
### Configuration for the DApp

1. **Copy and Paste ABI**
   - Copy the ABI (Application Binary Interface) of the staking contract and stake token contract.
   - Paste the ABI files into the `src/ABI` folder.

2. **Update Contract Addresses**
   - Update the contract addresses of the staking contract and stake token in the `utils/connectWallet.jsx` file.

### Running the DApp Locally

1. **Navigate to the Client Directory**
   ```bash
   cd client
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start the Development Server**
   ```bash
   npm run dev
   ```
## Contact
For any questions or inquiries, feel free to reach out to [Kshitij] at [https://twitter.com/KshitijWeb3].
---
