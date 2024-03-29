# Decentra Drive
#
![DecentraDriveIMG](https://user-images.githubusercontent.com/83500098/231229815-c25081a8-cc78-42c1-bed5-f5784ee3a4a4.png)
Decentralized file storage system.

A powerful smart contract that allows for decentralized file storage on the Ethereum blockchain. A user can interact with the front end and upload files to IPFS using Pinatas API. Generate CIDs and store metadata conveniently across a network of nodes with the click of a button. Allows for toggle view access to any specific Ethereum address, granting them or revoking access rights to your files. Think of this as a decentralized Google Drive, web3 style.
#

Technologies Used:
- JavaScript
- Ethers.js
- React.js
- Solidity
- Hardhat
- IPFS

#

To run this program you will need the following:
1. Metamask account (save your private key inside of a dotenv file). https://metamask.io/
2. Pinata account (save your API and Secret Key inside of a dotenv file). https://www.pinata.cloud/
3. Clone this repo to your local device and CD into that folder.
4. Run: `npm install` from the main directory.
5. CD into the "client" folder and run: `npm install`
6. CD back to the main directory and create a dotenv file (see example) input all of the parameters.
7. Compile the smart contract from the main directory: `npx hardhat compile`
8. Deploy smart contract on Ethereum Goerli testnet and run this command: `npx hardhat run scrips/deploy.js --network goerli`
9. CD back to the "client" folder and run: `npm run start` App will launch from a new browser window.

Try running some of the following optional tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
