# Simple Token and Vault Smart Contracts

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The `ERC20 Token` and the `Vault` smart contract is a simple example of an Ethereum-based token with basic functionalities to mint and burn tokens as well as deposit and withdraw functions. It is designed for educational purposes and can be used as a starting point for creating your token contracts.

Thos contract was used to demonstrate and experiment on an Avalanche Subnet task.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Contract Details](#contract-details)
- [Functions](#functions)

## Overview

The `ERC20 Token` contract provides a minimalistic ERC-20-like token implementation with the following features:

- Token name: "Solidity by Example"
- Token abbreviation: "SOLBYEX"
- Total supply management
- Minting tokens
- Burning tokens

The `Vault` contract provides a minimalistic vault system with the following features:
- Deposit Tokens
- Withdraw Tokens
- Interaction with the Token Contract through the `IERC20` interface.

## Getting Started

To deploy and interact with the `ERC20` contract, you can follow these steps:

1. **Clone the Repository**: Clone this repository to your local environment.

2. **Compile and Deploy**: Compile the contract using a Solidity compiler and deploy it to an Ethereum network of your choice. You can use development tools like Remix. Deploy the `ERC20 token` contract first, then copy its address and deploy the `Vault` contract passing the copied address into its constructor.