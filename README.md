# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```

## get key

Step1: Add require("@nomiclabs/hardhat-etherscan");
Step2: Add your Bscscan API key. Register and obtain your API key from <https://bscscan.com/myapikey> .
Step3: Always remember to set the solidity compiler version to match what was used for deploying the smart contract.

## verify bsc

npx buidler verify --network mainnet DEPLOYED_CONTRACT_ADDRESS "Constructor argument 1"
