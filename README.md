# FundSplitter

<p style="text-align: center;"><img src="https://img.shields.io/github/last-commit/0xRian/FundSplitter"></p>

## Disclaimer

This smart contract is for splitting incoming funds to other ETH addresses. e. g. this [(smart contract)](https://mumbai.polygonscan.com/address/0x86c5f827a306ad2b7af005049009535dc82bf924#code)

## Usage

- Compile the smart contract with the latest solidity version (0.8.15).

- Go to the deployment section and select "Injected Provider - MetaMask" as your environment.

- Sign in to your [MetaMask](https://metamask.io/) wallet and create two new wallets.

- Copy the two wallet addresses to the field that says ```address[] _address``` (Array) next to the Deploy button.

## Testing

- Go to your deployed contracts and open your created smart contract.

- Use indexing to get the address (e. g. 1: ```address: 0x...```)

- In this case only two addresses will work because only two addresses have been inserted.

## Uploading Code to Mumbai PolygonScan 

- Go to the the MetaMask wallet where the smart contract was uploaded from.

- Get the Transaction ID and look it up at [PolygonScan](https://mumbai.polygonscan.com/).

- Paste the Transaction ID and go to the contract.

- Paste your ```code``` at the contract section and go with the settings you applied for remix at the beginning.
