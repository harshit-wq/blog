# Edge Contracts
### Pre Requisites

Before running any command, make sure to install dependencies:

```sh
$ npm install
```

### Testing
Move to directory and use:

```sh
$ npx hardhat test
```

### Deployment

Make sure you have all dependencies installed, and configured .env , then use
```sh
$ npx hardhat run --network matic scripts/deploy.js
```

### Verification

Make sure you have all dependencies installed, configured .env and deployed contract addres then use
```sh
$ npx hardhat verify --network matic <DEPLOYED_CONTRACT_ADDRESS>
```
