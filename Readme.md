# Meme Coin DAPP
This is the Solidity SmartContract + React.js code for the Meme Coin DAPP 😙

## How to work 👷
- Anybody can MINT own Token as a Token Owner
- Token Owner can BURN and TRANSFER Token to others
- Token Holders can TRANSFER Token

## Getting setup ⚙️
- Copy `.env` file to `.env.local`
- Create an App in [Pork Portal](https://www.portal.pokt.network/) and Update *PORK_RINKEBY_URL* in `.env.local`
- Copy your metamask Rinkeby account private key and Update *RINKEBY_PRIVATE_KEY* in `.env.local` 🤫
- Run `npm install`

## Deploy Smart Contract 🐶
- Update CoinName, CoinTicker and TotalSupply in `contracts/MemeCoin.sol` file
- Compile Smart Contract: `npx hardhat compile`
- Deploy Smart Contract to Rinkeby Testnet: `npx hardhat run scripts/deploy.js --network rinkeby`

## Running React App 🍪
- Copy `MemeCoin.json` file from `artifacts/contracts/MemeCoin.sol/` to `src/abi/`
- Update contractAddress variable in `src/App.js` file with deployed Contract Address
- Run `npm start` and Enjoy 👌



