# Fund Me - A Web3 Funding Application

## Overview

Fund Me is a decentralized funding application built on the Ethereum blockchainl developed using Hardhat. It allows users to fund this contract and withdraw funds. This README provides information on how to set up and run the application.


## Live Link
[Fund Me Live](https://fund-me-eth.on.fleek.co/)

## Getting Started

To run the Lottery application locally, follow these steps:

   Clone this repository to your local machine:

   ```bash
   git clone https://github.com/kaviraj-j/hardhat-fund-me.git
   ```
   Change into the project directory:

   ```bash
   cd hardhat-smartcontract-lottery
   ```
   Install project dependencies using Yarn:

   ```bash
   yarn install
   ```

   Compile the Contract and Deploy them to a testnet or local-hardhat

   ```bash
   yarn hardhat compile
   ```

   ```bash
   yarn hardhat deploy --network <network-name>
   ```

   Note: Before deployment configure the environmental variables (.env)



## Client application

Clone the front end application from this repo

[Click here - Client](https://github.com/kaviraj-j/client-fund-me)