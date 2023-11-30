# Ethereum Smart Contracts, Tokens, and Dapps

**A Decentralized Star Notary Service Project**

This project implemetns a DApp that allows a user to create, buy, sell, transfaer, and exchange a Star NFT. The DApp creates a new Token.

Token Name:

```
To The Stars
```

Token Symbol:

```
TTS
```

Token Address:

```
0x93cF62325BD6283e8cb37CD87D7E79C3A0eF7461
```

## Technologies

```
Truffle v5.11.5
Truffle-hdwallet-provider 1.0.17
Openzeppelin-solidity 3.0
```

## How to Run this DApp

### Initial Setup

1. Obtain an API Key from Infura:

```
https://infura.io
```

2. Get the `network_id` for the test network you'll be using. In this project, the Sepolia Test Network is used.

3. Obtain your metamask Mnemonic

4. Update the file `truffle-config.js` with the values from 1-3 above.

### Running the application

1. Installation

```bash
cd app

# install all modules listed as dependencies in package.json
npm install
```

2. Start Truffle by running

```bash
# For starting the development console
truffle develop

# For compiling the contract, inside the development console, run:
compile

# For migrating the contract to the locally running Ethereum network:
migrate --reset

# For migrating the contract to the test network Sepolia:
migrate --reset --network sepolia

# For running unit tests the contract, run:
test
```

3. Frontend - Once you are ready to start your frontend, run the following from the app folder:

```bash
cd app
npm run dev
```

Test the DApp in your browser by going to:

```
http://localhost:8080/
```

---

### Metamask Setup

You need to add two new networks in your Metamask client. Here is the required information for both:

1. Local Truffle Network

| Network Name          | New RPC URL              | Chain ID |
| --------------------- | ------------------------ | -------- |
| Truffle Local Network | `http://127.0.0.1:9545/` | 1337     |

2. Sepolia Test Network

| Network Name         | New RPC URL                     | Chain ID |
| -------------------- | ------------------------------- | -------- |
| Sepolia Test Network | `https://sepolia.infura.io/v3/` | 1        |
