# DIOToken

## Overview

DIOToken (DIO Coin) is an ERC-20 compliant token implemented in Solidity. It follows the ERC-20 standard, enabling interoperability with other smart contracts and decentralized applications (dApps) on the Ethereum blockchain.

## Token Details

1. Token Name: DIO Coin

2. Token Symbol: DIO

3. Decimals: 2

4. Total Supply: 1,000,000 DIO

## Smart Contract

The DIOToken smart contract is implemented with the following functionalities:

1. totalSupply(): Returns the total supply of the tokens.

2. balanceOf(address tokenOwner): Returns the balance of a specific account.

3. allowance(address tokenOwner, address spender): Checks the amount of tokens that an owner allowed to a spender.

4. transfer(address to, uint tokens): Transfers tokens from the caller's account to another account.

5. approve(address spender, uint tokens): Allows a spender to transfer tokens from the caller's account.

6. transferFrom(address from, address to, uint tokens): Transfers tokens from one account to another, utilizing the allowance mechanism.

## Contract Code

<img src="https://github.com/user-attachments/assets/1d8e0545-5d50-4437-828a-1feaa85c9116" alt="Carbon"/>

## Usage

Deploy the Contract:

Use an Ethereum development environment like Remix, Truffle, or Hardhat to deploy the DIOToken contract.

## Interacting with the Contract:

1. Check total supply: totalSupply()

2. Check balance: balanceOf(address tokenOwner)

3. Transfer tokens: transfer(address to, uint tokens)

4. Approve tokens: approve(address spender, uint tokens)

5. Transfer tokens from: transferFrom(address from, address to, uint tokens)

## Events:

1. Transfer Event: Emitted when tokens are transferred.

2. Approval Event: Emitted when an approval is made.

## Compiling

Compiling via Remix - Ethereum IDE

![REMIX](https://github.com/user-attachments/assets/4faa4a09-64e5-4d9f-a64b-c7085fa0f0d2)

## License

This project is licensed under the GPL-3.0 License.
