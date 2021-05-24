# Project 1: completing smart contract developement
# Project 2: Smart Contract Testing

This project is part of the Blockchain Specialization at Coursera. The test cases has been added in this project in continuation of the project done in Course 2 (which allows bidding of items by participants and its various functions such as register bidder, declare winner etc. over blockchain).

More details can be found here:

**[Project Description](./Project_Description.pdf)**

# How to run?

## Pre-requisites
- Ubuntu 20.04
- Git installed
- Truffle framework installed 

## Run Project 1
- open a new Bash terminal 
- Clone this repository using command: `git clone https://github.com/Safieddine90/Coursera-Blockchain-Specialization.git`
- Checkout the correct branch using command: `git checkout project1`
- run `truffle develop` in the terminal
- Open another terminal and run the following commands:
  - `truffle compile`
  - `truffle migrate --reset`
  - If done correctly as specified, it should build the smart contract and allow to interact with it throught the web interface
  
## Run Project 2
- open a new Bash terminal 
- Clone this repository using command: `git clone https://github.com/Safieddine90/Coursera-Blockchain-Specialization.git`
- Checkout the correct branch using command: `git checkout project1`
- run `truffle develop` in the terminal
- Open another terminal and run the following commands:
  - `truffle compile`
  - `truffle migrate --reset`
  - `truffle test` 
- If done correctly as specified, all test cases related to the Smart Contract functions such as registering bidders, placing bids and revealing winners should pass.

# Technology Stack
This project uses the following technologies:
- **Solidity v0.4.17**
- **Truffle IDE v4.0.4**


# License
- This project is a public domain work, dedicated using CC0 1.0. 