# Decentralized File Storage

Dropbox clone running with solidity ߷⛓️.

## Dependencies

You need NodeJS, Truffle, Ganache, ReactJS and Metamask to run the project

### NodeJS installation (I used node 16.14.0) : 
[Install NodeJS](https://nodejs.org/en/)

### Truffle installation : 
```bash
npm install -g truffle
```
### Ganache installation : 
[Install Ganache](https://trufflesuite.com/ganache/?utm_source=devportal)

### Metamask installation : 
[Install Metamask](https://metamask.io/)


## Run the project
First, launch Ganache and make sure your Metamask is connected to your Ganach local blockchain.

##### In the first terminal :computer: :
```bash
git clone https://github.com/Sidouuuux/Solidity-Dropbox.git
cd Solidity-Dropbox
npm install
npm run start
```

##### In the second terminal :computer: :
```bash
cd Solidity-Dropbox
truffle migrate --reset
```

##### To run tests 🧪 on the smart contract 📋 :
```bash
cd Solidity-Dropbox
truffle test
```

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.
