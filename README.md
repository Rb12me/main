# Defi App
Construction of a basic cryptocurrency staking dapp. In this app you will receive DApp Tokens in the form of rewards for storing DAI (the DAI used is a smart contract that emulates the real DAI).

Frameworks: Truffle, React
Test Network: Ganache
Testing: Chai (chai-as-promised)
DAppTokenFarm

Useful commands:
Install dependencies (First thing to do if you download this project):

 npm install
Compile the smart contracts:

 truffle compile
Upload all contracts back to the blockchain replacing the previous ones

 truffle migrate --reset
Execute a .js script

 truffle exec <path>
Run tests

 truffle test
start local web server (inside the defi_tutorial project)

 npm run start
