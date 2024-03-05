# Avalanche Subnets

## Overview
ERC20 Contract:
Basic ERC-20 token with standard functionalities.
Implements transfer, approve, transferFrom, mint, and burn.
Introduces a shield mechanism (activate) and shooting functionality (shoot).
Tracks token balances, allowances, and metadata.

Vault Contract:
Manages deposit and withdrawal of tokens in a vault.
Users deposit tokens to receive proportional shares.
Shares can be used to withdraw tokens.
Basic implementation for a token vault.

## Description
ERC20 Contract:
The ERC20 contract defines a basic ERC-20 token with additional functionalities. It includes standard ERC-20 operations such as transferring tokens (transfer), approving  
token spending (approve), and transferring tokens on behalf of someone else (transferFrom). The contract introduces custom features like minting new tokens (mint), burning
tokens (burn), activating a shield (activate), and shooting the token to decrease its health (shoot). The contract also maintains information about token balances, allowances
and metadata such as the token name, symbol, and decimals.

Vault Contract:
The Vault contract manages the deposit and withdrawal of tokens in a vault-like structure. Users can deposit tokens into the vault and receive proportional shares in return.
Shares can be later used to withdraw tokens. The contract maintains the total supply of shares and individual share balances for each user. It provides a basic implementation
of a token vault.

Interfaces:
The IERC20 interface defines the standard ERC-20 functions, facilitating interoperability with other contracts or systems.

## Executing program
1. Set Up Development Environment:
Install Node.js and npm:
Ensure that you have Node.js and npm (Node Package Manager) installed on your machine. You can download them from Node.js website.
Install Hardhat:
Open a terminal and run the following command to install Hardhat globally:
2. Create a New Hardhat Project:
Initialize a New Hardhat Project:
Create a new directory for your project and navigate to it in the terminal.
Run the following command to initialize a new Hardhat project:
3. Replace Hardhat Configuration:
Replace hardhat.config.js:
Replace the content of the generated hardhat.config.js

To execute the provided Solidity code, you'll need to perform the following steps:

1. Set Up Development Environment:
Install Node.js and npm:
Ensure that you have Node.js and npm (Node Package Manager) installed on your machine. You can download them from Node.js website.
Install Hardhat:
Open a terminal and run the following command to install Hardhat globally:
bash
Copy code
npm install -g hardhat
2. Create a New Hardhat Project:
Initialize a New Hardhat Project:
Create a new directory for your project and navigate to it in the terminal.
Run the following command to initialize a new Hardhat project:
bash
Copy code
npx hardhat
Choose "Create an Ethereum project" and follow the prompts.
3. Replace Hardhat Configuration:
Replace hardhat.config.js:
Replace the content of the generated hardhat.config.js file with the following code:
javascript
Copy code
module.exports = {
  solidity: "0.8.17",
};
4. Add Solidity Contracts:
Replace contracts Folder:
Replace the contracts folder in your project with the provided ERC20.sol and Vault.sol files.

To execute the provided Solidity code, you'll need to perform the following steps:

1. Set Up Development Environment:
Install Node.js and npm:
Ensure that you have Node.js and npm (Node Package Manager) installed on your machine. You can download them from Node.js website.
Install Hardhat:
Open a terminal and run the following command to install Hardhat globally:
bash
Copy code
npm install -g hardhat
2. Create a New Hardhat Project:
Initialize a New Hardhat Project:
Create a new directory for your project and navigate to it in the terminal.
Run the following command to initialize a new Hardhat project:
bash
Copy code
npx hardhat
Choose "Create an Ethereum project" and follow the prompts.
3. Replace Hardhat Configuration:
Replace hardhat.config.js:
Replace the content of the generated hardhat.config.js file with the following code:
javascript
Copy code
module.exports = {
  solidity: "0.8.17",
};
4. Add Solidity Contracts:
Replace contracts Folder:
Replace the contracts folder in your project with the provided ERC20.sol and Vault.sol files.
5. Run Deployment Script:
Create a Deployment Script:
Create a new JavaScript file in the scripts folder, for example, deploy.js.
Copy and paste the deployment script into deploy.js.
6. Interact with Deployed Contracts:
Use a Development Console:
You can use the Hardhat console or a tool like Remix to interact with the deployed contracts.
Modify Contracts or Scripts:
Modify the contracts or deployment scripts as needed and repeat the deployment process.
7. Additional Notes:
Testing:
Consider writing tests for your contracts using the Hardhat testing framework.
Network Configuration:
You can configure additional networks in the hardhat.config.js file for deploying to different Ethereum networks.

## Help
1. Environment Setup:
Ensure Node.js and npm are installed on your machine.
Install Hardhat globally using npm install -g hardhat.
2. Hardhat Project Initialization:
Initialize a new Hardhat project using npx hardhat and choose "Create an Ethereum project."
3. Solidity Contracts:
Replace the content of the contracts folder with the provided ERC20.sol and Vault.sol files.
Understand the functionalities and custom features introduced in the contracts, such as shield activation, shooting, depositing, and withdrawing from the vault.
4. Hardhat Configuration:
Modify the hardhat.config.js file if needed.
Ensure the specified Solidity version is compatible with the contracts.
5. Deployment Script:
Create a deployment script in the scripts folder (e.g., deploy.js).
Copy and paste the deployment script provided.
6. Interact with Contracts:
Use the Hardhat console or Remix to interact with the deployed contracts.
Test contract functionalities, such as transferring tokens, activating the shield, shooting, depositing, and withdrawing from the vault.
7. Customization:
Customize the contracts or deployment scripts based on your specific use case.
Consider adding additional functionalities or modifying existing ones.
8. Testing:
Write tests for the contracts using the Hardhat testing framework to ensure their correctness.
Conduct thorough testing before deploying contracts on a mainnet.
9. Network Configuration:
Understand the network configuration in hardhat.config.js and adjust it for deploying to different Ethereum networks.
Be cautious when deploying to a live network; use testnets for initial testing

## Authors
H N GAGAN
gaganhn2004@gmail.com

## License
This project is licensed under the MIT License



