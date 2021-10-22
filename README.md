# decentralized-exchange-project

![DEX](https://user-images.githubusercontent.com/83671629/138368750-a9cfd0ad-2577-425b-8450-04770c05be6a.jpg)

# Introduction 

Although centralized exchanges [CEXs](https://www.investopedia.com/tech/what-are-centralized-cryptocurrency-exchanges/) currently dominate cryptocurrency trading activity, decentralized exchanges [DEXs](https://www.investopedia.com/terms/d/decentralizedmarket.asp) are growing in popularity. DEXs facilitate peer-to-peer trading by relying on automated smart contracts to execute trades without an intermediary.
Decentralized exchanges take a different approach to buying and selling digital assets: They operate without an intermediary organization for clearing transactions, relying instead on self-executing smart contracts to facilitate trading. This dynamic enables instantaneous trades, often at a lower cost than on centralized crypto exchanges.

To put it simply, decentralized exchanges (DEXs) enable users to buy and sell cryptocurrencies with one another without the need for brokers. Users merely need to connect their crypto wallet to a DEX, such as Uniswap [CRYPTO:UNI](https://uniswap.org/) or PancakeSwap [CRYPTO:CAKE](https://pancakeswap.finance/), select their crypto-crypto trading pair of choice, such as between Bitcoin and Ethereum, enter the amount, and hit the swap button. 

In this project we have made an attempt to exactly do that, create a decentralized exchange platform.

### Dependencies / Requirements

- Truffle 
- Solidity 
- Node js
- Web3.js 
- Ganache 
- npm
- sublime text

The detailsed dependencies and there versions can be found in this file ![package.json
](package.json)


### Initial Setup

1. cd into project directory
2. Run `npm install`


### Set Up Ganache



### Set Up Accounts

![Orders Architecture](./assets/ganache1.png) ![Orders Architecture](./assets/ganache2.png)

1. Open up Metamask and add a new Custom RPC

![Orders Architecture](./assets/ganache3.png)

2. The RPC URL can be found on Ganache

![Orders Architecture](./assets/ganache4.png)

![Orders Architecture](./assets/ganache.png)

3. Import the first account on Ganache to your Metamask. The private key of that account can be found by clicking on the 'key' icon on Ganache
4. You can add all the accounts in Ganache to simulate multiple users.
5. Only the first account is the owner account which deployed all the contracts. This will be the account that will have the initial supply of SCSE, MAE and EEE tokens.
6. If you do not see the ETH being reflected in your Metamask wallet, change to another network and change back to Ganache

### Set Up Website

1. cd into 
2. Run `npm install`
3. Run `npm run start` in console
4. If all token balances are 0 in the website, make sure your Metamask account is connected to the website

