# solid-giggle

## Description
A multi-signature wallet smart contract written in Solidity for the Ethereum Blockchain
* A multi-signature wallet is one where anyone can deposit token into however only owners of the wallet can transfer any token out as long as they have a minimum number of approvals from the co-owners of the wallet as specified during the contract instantiation at the time of deployment
* At the time of contract creation, the owner addresses and minimum approvals needed for a transfer must be set, like so:

["0x5B38Da6a701c568545dCfcB03FcB875f56beddC4", "0xAb8483F64d9C6d1EcF9b849Ae677dD3315835cb2", "0x4B20993Bc481177ec7E8f571ceCaE8A9e22C02db"], 3

The above inputs indicate the three addresses that are going to be the *owners* of this wallet and that all 3 owners must approve a transfer for it to be successful.

## Running the code
Simply copy the code from both .sol files into Remix IDE and get going :) 

## Contribution
Feel free to create a PR in case you come across any issues!

## Licensing
Please read the LICENSE document for more details on how you can use this code.