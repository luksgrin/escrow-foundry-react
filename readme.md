# Decentralized Escrow Application

This is an Escrow Dapp built with [Foundry](https://github.com/foundry-rs/foundry).

## Project Layout

There are five top-level folders:

1. `/app` - contains the front-end application
2. `/lib` - contains the smart contract dependencies
3. `/script` - contains the deployment scripts
4. `/src` - contains the solidity contract
5. `/test` - contains tests for the solidity contract

## Setup

> This setup assumes you have foundry installed and running properly

Install dependencies in the top-level directory with `git submodule update --init --recursive`.

Compile the contracts using `forge compile`. The artifacts will be placed in the `/app` folder, which will make it available to the front-end. This path configuration can be found in the `foundry.toml` file.

## Front-End

`cd` into the `/app` directory and run `npm install`

To run the front-end application run `npm start` from the `/app` directory. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.