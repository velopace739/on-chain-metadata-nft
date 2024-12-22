# On-Chain Metadata NFT contract

This repo contains a contract that implements tipping functionality.

Install dependencies with `yarn`.

Set up by creating a `.env` file, and filling out these variables:

```
TESTNET_RPC=your Alchemy RPC URL
PRIVATE_KEY=your wallet private key
BSCSCAN_API_KEY=your bscscan api key
```

You can get an Alchemy RPC URL for free [here](https://dashboard.alchemy.com/).

## !!! Be very careful with exporting your private key !!!

You can get your Private Key from MetaMask [like this](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key).
If you have any questions or concerns about this, please find someone you trust to sanity check you! 

## !!! Be very careful with exporting your private key !!!

Deploy your contract with:

```
npx hardhat run .\scripts\deploy.ts --network bsc_testnet
```
Verify your contract with:
```
npx hardhat verify --network bsc_testnet CONTRACT_ADDRESS
```

## Contract Address
BSC testnet:
[0x572Fc2562DB5fBD83D44419c588F486f74773b27](https://testnet.bscscan.com/address/0x572Fc2562DB5fBD83D44419c588F486f74773b27#code)
