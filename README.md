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

The detailed dependencies and there versions can be found in the file [package.json
](package.json)


### Initial Setup

1. Go to "disc C" and create directory named "project pr0"
2. Run the following under Powershell "as administrator" 
    * ` dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart `
    * ` dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart `
    * ` Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All `
      Restart your computer
3. Download and Install [WSL2](https://docs.microsoft.com/en-us/windows/wsl/install)
4. Download and Install [Ganache](https://www.trufflesuite.com/ganache)
5. Download, Install and Launch **Ubuntu from Microsoft Store**
6. Download and Install **Windows Terminal from Microsoft Store**
    * Go To settings, paste the contents of [settings.json](settings.json and save file
    * Run: `sudo apt-get update`
    * Run: `sudo apt install python2`
    * Run: `sudo apt-get install build-essential`
    * Run: `echo "alias subl='"'"/mnt/c/Program Files/Sublime Text 3/subl.exe"'"'" >> ~/.bashrc`
    * Run: `echo "alias npms='CHOKIDAR_USEPOLLING=true npm start'" >> ~/.bashrc`
    * Run: `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.1/install.sh | bash`
    * Restart Windows Terminal
    * Run: `nvm install 10.19.0`
    * Run: `npm i -g truffle`

### Set Up MetaMask and Ganache Accounts

1. Open and install [MetaMask](https://metamask.io/)
2. Import the first account on Ganache to your Metamask. The private key of that account can be found by clicking on the 'key' icon on Ganache
3. You can add all the accounts in Ganache to simulate multiple users.
4. Only the first account is the owner account which deployed all the contracts. This will be the account that will have the initial supply of tokens.
5. If you do not see the ETH being reflected in your Metamask wallet, change to another network and change back to Ganache

### Set Up Website

1. cd into "project pr0"
2. Run `npm install`
3. Run `npm run start` in console
4. If all token balances are 0 in the website, make sure your Metamask account is connected to the website

![DIAGRAM](https://user-images.githubusercontent.com/83473146/138620527-0b4b28ee-6bf3-49c5-8fe6-2af179d30564.png)
