# Decentralized Star Notary Project

The project implementation is according to the [Project Rubric](https://review.udacity.com/#!/rubrics/2297/view).


## Project Specification

* Truffle: v5.1.58
* OpenZeppelin/contracts: v3.3.0
* Solidity: 0.7.4 (solc-js)
* Node: v12.13.1
* Web3.js: v1.2.9
* ERC-721 Token Name: "Decentralized Star Notary Nikos"
* ERC-721 Token Symbol: "DSNN"
* “Token Address” on the Rinkeby Network: https://rinkeby.etherscan.io/address/0xdd0fc501f1818cb01de5f7f21ef2488c7690ef65


## Running the project locally

Open the package-lock.json and verify that truffle-hdwallet-provider and openzeppelin-solidity dependencies are installed. If not you can always install it with the commands:
```
npm install --save truffle-hdwallet-provider
npm install --save-dev @openzeppelin/contracts
```

For starting the development console, run:
```
truffle develop
```

For compiling the contract, inside the development console, run:
```
compile
```

For migrating the contract to the locally running Ethereum network, inside the development console, run:
```
migrate --reset
```

For running unit tests the contract, inside the development console, run:
```
test
```

For running the Front End of the DAPP, open another terminal window and go inside the project directory, and run:
```
cd app
npm run dev
```