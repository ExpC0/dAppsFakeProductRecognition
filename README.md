# dAppsFakeProductRecognition
Blockchain based system project

Here is the complete README file content in one block:

```markdown
# Fake Product Identification

## Overview
This project aims to provide a decentralized application (dApp) to identify and verify the authenticity of products using blockchain technology.

## Required Packages
- Truffle v5.6.7 (core: 5.6.7)
- Ganache v7.5.0
- Solidity v0.5.16 (solc-js)
- Node v15.8.0
- Web3.js v1.7.4
- npm 7.5.1

## Setup Instructions



2. **Navigate to the Project Directory**
   Open your terminal in the project folder and install the necessary node modules:
   ```bash
   npm install
   ```

3. **Compile the Smart Contracts**
   Use Truffle to compile the contract source files:
   ```bash
   truffle compile
   ```

4. **Set Up Ganache**
   - Open Ganache.
   - Create a new workspace.
   - Add `truffle-config.js` to the Truffle project.
   - Change the server port to 7545 in Ganache settings to match the port in `truffle-config.js`.

5. **Configure MetaMask in Chrome**
   - Open MetaMask and add a new test network:
     - Network ID: `5777` (from Ganache server settings)
     - RPC Server: `http://127.0.0.1:8545` (from Ganache server settings)
     - Chain Code: `1337`
   - Import an account using the private key from one of the accounts in Ganache's local blockchain.

6. **Deploy the Smart Contracts**
   In the terminal, run the following commands:
   - Migrate the contracts:
     ```bash
     truffle migrate
     ```
   - Start the development server:
     ```bash
     npm run dev
     ```

7. **Connect MetaMask to the Local Blockchain**
   Log in to MetaMask and connect the imported account to the local blockchain (`localhost:3000`).

8. **Interact with the Website**
   Open the application and begin interacting with it through your browser.

## Contributors
- Md. Robayed Molla
- contact:[https://github.com/Robayed110]
- Md. Raduan Islam Rian
- contact:[https://github.com/ExpC0]


