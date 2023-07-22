# Creating ERC-20 Tokens

## Description

We have created an ERC-20 Tokens, the token name is "DEGEN" and the token abbrv is "DGN". The token has certain functionalities: 
* Only the owner of the contract can mint the tokens.
* Anyone who has the tokens can tranfer their tokens to a certain account.
* The account that possess the tokens can check the token balance.
* The user who has the tokens can redeem for certain Badges.
* At the last, anyone can burn the tokens which are no longer needed.

## Getting Started

Clone this github repository, using the below command in your cmd. Make sure you have git installed. 

```
git clone [paste the link to the repo]
```

### Installing

* Install all the dependencies needed.

```
npm install 
```

### Executing program

* Deploy the contract on the fuji Testnet 
```
npx hardhat run scripts/deploy.js --network fuji
```
* Once you have deployed the contract, you can now interact with the contract using online Remix IDE. 
* Also, connect your metamask wallet to transact on the Testnet.

## Help

Make sure you watch the tutorials properly for a better understanding of the concept.

## Authors

Alpesh Dongre

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
