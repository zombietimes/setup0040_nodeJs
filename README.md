# [setup0040_nodeJs](https://github.com/zombietimes/setup0040_nodeJs)
This script file is for setting up the DApps development environment on Ubuntu.  

## Overview
[setup0040_nodeJs](https://github.com/zombietimes/setup0040_nodeJs) is one of the script files for setting up the development environment on Ubuntu desktop.  
[setup0040_nodeJs](https://github.com/zombietimes/setup0040_nodeJs) is a part of [setup0000_all](https://github.com/zombietimes/setup0000_all).  
The role of [setup0040_nodeJs](https://github.com/zombietimes/setup0040_nodeJs) is to set up node.js.  

## Description
Let's set up the DApps development environment on your local computer by using this script file.  
I think that it is worth learning the smart contract development.  
I focus on Ethereum and Loom Network as the DApps.  

### node.js
node.js is the server side platform of JavaScript.  
- [node.js : Official](https://nodejs.org/en/)  

### npm
npm supports to manage the application version of node.js.  
- [npm : Official](https://www.npmjs.com/)

### NVM : Node Version Manager
NVM supports to manage the application version of node.js and npm.  
If you want to use NVM, use [setup0041_nvm](https://github.com/zombietimes/setup0041_nvm) instead of [setup0040_nodeJs](https://github.com/zombietimes/setup0040_nodeJs).  
- [NVM : Official](https://github.com/nvm-sh/nvm)
- [setup0041_nvm](https://github.com/zombietimes/setup0041_nvm)

### yarn
yarn supports to manage the application version instead of npm.  
If you want to use yarn, use [setup0042_yarn](https://github.com/zombietimes/setup0042_yarn) too.  
- [yarn : Official](https://yarnpkg.com/en/)
- [setup0042_yarn](https://github.com/zombietimes/setup0042_yarn)

### Constitution
[setup0000_all](https://github.com/zombietimes/setup0000_all) is the instruction script file to run the other script files.  
[setup0000_all](https://github.com/zombietimes/setup0000_all) consists of the external script files below.  
- [setup0010_directory](https://github.com/zombietimes/setup0010_directory)
- [setup0020_ubuntu](https://github.com/zombietimes/setup0020_ubuntu)
- [setup0030_loomNetwork](https://github.com/zombietimes/setup0030_loomNetwork)
- [setup0040_nodeJs](https://github.com/zombietimes/setup0040_nodeJs) : Here!
- [setup0050_truffle](https://github.com/zombietimes/setup0050_truffle)
- [setup0060_openZeppelin](https://github.com/zombietimes/setup0060_openZeppelin)
- [setup0070_ganache](https://github.com/zombietimes/setup0070_ganache)
- [setup0080_express](https://github.com/zombietimes/setup0080_express)

### Environment
This script file is for Ubuntu(Linux).  
I recommend that you use VirtualBox + Ubuntu.  

### Sample DApps
I created some sample smart contracts below.  
I hope to be useful to you when you develop DApps.  
- [Hello world : HelloZombies.sol](https://github.com/zombietimes/dapp_helloWorld)
- [ERC20 : Coin20.sol](https://github.com/zombietimes/dapp_erc20)
- [ERC721 : Asset721.sol](https://github.com/zombietimes/dapp_erc721)
- [Multi contract : ImportZombies.sol](https://github.com/zombietimes/dapp_multiContract)
- [Sending Ether](https://github.com/zombietimes/dapp_sendEther)

## Usage
Run the command on Ubuntu console window.  
```sh
# Ubuntu commands.
git clone https://github.com/zombietimes/setup0040_nodeJs.git
cd setup0040_nodeJs
sh ./ubuntuCmd_setupNodeJs.sh
```
![setup0040_nodeJs_0000](https://user-images.githubusercontent.com/50263232/57186248-a3d32c00-6f16-11e9-882f-6ec06133a1e6.png)  

## Requirement
I confirmed that it works on Ubuntu Desktop 18.04 in VirtualBox.  
It works on the environment below.  
- On Ubuntu.
- Google Chrome.

## Relative link
### Overview
- [Ethereum : Official](https://www.ethereum.org/)
- [Ethereum : Wikipedia](https://en.wikipedia.org/wiki/Ethereum)
- [Loom Network : Official](https://loomx.io/)
- [Loom Network : Binance wiki](https://info.binance.com/en/currencies/loom-network)

### Development
- [Online editor : EthFiddle](https://ethfiddle.com/)
- [Online editor : Remix](https://remix.ethereum.org/)

### Learning
- [Online learning : CryptoZombies](https://cryptozombies.io/)
- [Grammar : Solidity](https://solidity.readthedocs.io/)
- [Grammar : Best Practices](https://github.com/ConsenSys/smart-contract-best-practices)

### DApps
- [DApps : CryptoKitties](https://www.cryptokitties.co/)
- [DApps : Zombie Battle ground](https://loom.games/en/)

## Messages
Do you believe that the decentralized world is coming?  
When do you use [DApps](https://en.wikipedia.org/wiki/Decentralized_application)?  
Why?  

## License
BSD 3-Clause, see `LICENSE` file for details.  

