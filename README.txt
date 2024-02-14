Q.1) What is Hardhat?

Hardhat is a development environment used to ease the development of smart contracts and dapps.
Hardhat provides environment to develop, deploy, debug and test the smart contracts.
Hardhat runner which is a command line interface (CLI) tool can be used to interact with the 
hardhat environment such as using commands to run local hardhat network, compiling smart contracts,
testing, deploying, etc.

Q.2) Demonstrate the steps involved in the process of
installation and configuration of Hardhat Development
Environment.

steps:
1. Create a projects directory "app" in our case.
2. Change directory to "app" and run npm init.
3. Install hardhat using `npm install --save-dev hardhat` command.
4. To initialize and configure the hardhat environment run `npx hardhat init`. This will create seprate folders for contracts, tests, deploy scripts, etc. Screenshot is saved in "ss" directory
5. For further configuration "hardhat.config.js" can be edited to include networks such as local or mainnet using infura or alchemy rpc urls, accounts, plugins, etc.