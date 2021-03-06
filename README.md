# Vue Voting dApp

<p align="center">		
  <img src="https://github.com/marlowl/vue-truffle-starter-dapp/blob/master/logo.PNG">		
</p>
 
This project was generated with [vue-cli](https://github.com/vuejs/vue-cli) version 3.2.1

An Vue [truffle](https://github.com/trufflesuite/truffle) voting mechanism dApp

# Demo
![](screenshot.gif)

### Technologies & Languages Used
1. Vue (Both TypeScript and JavaScript component examples included)
2. Truffle (Solidity)
3. Ganache

# Project setup

### Ganache and Truffle (Both of these tools are required before moving forward)
```
npm install -g truffle ganache-cli
```
Simply start the ganache-cli with the following command
```
ganache-cli
```
### Install dependencies
```
git clone https://github.com/marlowl/vue-voting-dapp/
```
```
npm install
```

### Update the .env file
```
VUE_APP_ETHADDRESS= "your ETH address"
MNEMONIC= "your ganache MNEMONIC"
INFURA_API_KEY= "your infura key"
```

### Truffle: compile and migrate contracts
```
truffle compile
truffle migrate --network kovan
```
### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Run your unit tests
```
npm run test:unit
```
