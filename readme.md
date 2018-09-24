# Arestech Wallet

## About

Arestech wallet is a MultiCoin Wallet which is used to create , import and manage different Coins.

## Stack

Everything in this project is in JavaScript. 

### Client

- React
- React-router
- Redux
- CSS Module

### Server

- Node.js
- Express

## Running on your Machine

These instructions will get you a copy of the project up and running on your local machine for development or testing purposes.

### Prerequisites and Installation

- Node.js 
```bash
$ sudo apt-get update
$ sudo apt-get install nodejs
```

- npm 
```bash
$ sudo apt-get install npm
```

#### Check version
```bash
$ npm -v
(Require version 3.5.2^)
```
```bash
$ node -v 
(Require version v8^)
```

### Run Locally
Follow below steps to run the Application on local system.

Clone this project from the github repository and run below commands.

```bash
$ git clone https://github.com/christiangehl/arestech-wallet.git
```

```bash
$ cd client
(This command will change the directory where application will run locally)
```
```bash
$ npm install or sudo npm install
(This command will install all the dependencies from package.json File)
```
```bash
$ npm start
(This command will run the application on localhost:3000)
```

## Functionality List

### Generate Wallet
To create Wallet, go to **Generate Wallet** tab:
- click Generate Passphrase **Button**
- 12 Word Mnemonic passphrase and Ether Wallet address is generated
- copy and save both(mnemonic and address) for future use

### Wallet Info
To check the Wallet information, go to **Wallet Info** tab and Login: 
- To Login, enter the 12 Word Mnemonic.
- Wallet information like Wallet address , QR code of Wallet address, Ether balance is visible.

To check ERC20 Token Balance on the wallet address :
- click AddTokens **Button** and provide the token info like Contract address, Token symbol, decimal and click **Save**

### Send Ether
To do Ether Transaction, go to **Send Ether** tab and Login:
- To Login, enter the 12 Word Mnemonic.
- Fill the Information like Wallet Address and Amount to send the Ether.
- click Send Transaction **button**:

Transaction Successfull:
- If amount of Ether in Wallet >= (amount of Ether to send + gas price), Transaction hash is generated and equivalent amount of ether will be decuted from the wallet address. 

Transaction Failed:
- If amount of Ether in Wallet < (amount of Ether to send + gas price), Transaction fail and error message is shown.

#### Note:
Currently the Wallet is running in Rinkeby Test Network of Ethereum Blockchain. 