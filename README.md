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

Compile the Smart Contract!
```shell
npx hardhat compile
```

```shell
npx hardhat run scripts/deploy.ts --network base-goerli
```

For Mainnet
```shell
npx hardhat run scripts/deploy.ts --network base-mainnet
npx hardhat verify --network base-mainnet <YOUR_CONTRACT_ADDRESS>
```