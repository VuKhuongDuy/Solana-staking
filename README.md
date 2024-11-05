# Solana Stake Program

This is a **Solana stake program** developed using the [Anchor framework](https://project-serum.github.io/anchor/). This program allows users to stake SOL tokens to earn rewards over time. The Anchor framework provides a robust environment for developing and testing Solana programs with Rust.

## Table of Contents

- [Overview](#overview)
- [Program Features](#program-features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Directory Structure](#directory-structure)
- [Running Tests](#running-tests)
- [Deploying the Program](#deploying-the-program)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This staking program enables users to:
1. Stake SOL and earn rewards based on the staking duration.
2. Unstake SOL to retrieve their initial deposit along with any earned rewards.
3. View staking balance and status.

The program leverages Anchor's features for account management, instruction handling, and testing capabilities.

## Program Features

- **Stake SOL**: Users can deposit SOL into the staking program.
- **Earn Rewards**: Users earn rewards for keeping their SOL staked.
- **Unstake and Withdraw**: Users can unstake and withdraw their SOL along with any accrued rewards.
- **Account Management**: The program manages user accounts using Program Derived Addresses (PDA) for security and ownership verification.

## Prerequisites

To run and deploy this program, you will need:

- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Anchor CLI](https://project-serum.github.io/anchor/getting-started/installation.html)
- [Rust](https://www.rust-lang.org/tools/install)
- Node.js and Yarn (for running tests with Anchor's TypeScript testing framework)

Ensure Solana CLI and Anchor CLI are configured to connect to the appropriate Solana network (e.g., devnet, testnet, or mainnet-beta).

## Installation

Clone the repository and navigate into the project directory:

```bash
git clone <repository_url>
cd <repository_directory>
