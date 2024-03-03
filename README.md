# DApp ToDo List

A decentralized application (DApp) for managing a to-do list. The DApp is built on the Ethereum blockchain using Solidity smart contracts and a web-based user interface.

## Project Structure

The project consists of the following key components:

### Smart Contracts:

- Migrations.sol: A basic contract used for managing migrations.
TodoList.sol: The main contract for managing tasks on the to-do list.
Truffle Migration Scripts:

- 1_initial_migration.js: Deploys the Migrations contract.
- 2_deploy_contract.js: Deploys the TodoList contract.

### Front-End Web Application:

- app.js: JavaScript code for the web interface of the DApp.
index.html: The HTML template for the DApp's user interface.
Test Scripts:

- TodoList.test.js: Tests for the TodoList contract to ensure its functionality.

This DApp was created as part of a tutorial by Dapp University.
---
# React Truffle DApp Setup

## Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 12 or newer)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)
- [Truffle](https://www.trufflesuite.com/truffle) (installed globally)

You can check Node.js and npm versions by running `node -v` and `npm -v` in your terminal. For Truffle, run:

```bash
truffle version
```

## Setup

### 1. Clone the Repository

Clone your existing Truffle project repository to your local machine:

```bash
git clone https://github.com/yourusername/DApp-ToDo-List.git
cd DApp-ToDo-List-main
```

### 2. Install Dependencies

Install project dependencies for both Truffle and the React front end:

```bash
npm install
```

### 3. Configure Truffle

Ensure your Truffle configuration is set up correctly. This includes network configurations in the `truffle-config.js` file. Update it based on your blockchain network (e.g., Ganache, Ropsten, Mainnet).

### 4. Compile and Deploy Smart Contracts

Compile and migrate your smart contracts:

```bash
truffle compile
truffle migrate
```

### 5. Start the React App

Start the React development server:

```bash
npm run dev
```

This will launch your React application, and it should automatically open in your default web browser.

## Additional Information

- **Smart Contracts**: The smart contracts are located in the `contracts` directory. You can modify and add new contracts as needed.

- **React Front End**: The React front end is located in the `src` directory. Customize it based on your DApp requirements.