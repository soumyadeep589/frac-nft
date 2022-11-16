# frac-nft

There are 2 smart contract written in solidity. mynft.sol is for the nft itself and mytoken.sol is for the token based on ERC20.

mytoken holds all the necessary function to transfer token to another address, put for sale, purchase and redeem features.

* You need to deploy mynft.sol first in remix.
* mint nft with tokenId 1.
* Then you will deploy the token contract.
* Marked the SafeApprove function with token contract address in nft contract.
* Then initialize with nft address, token id and total supply.
* You can now transfer some of ERC20 token to new address.
* Mark putForSale true.
* Any one can buy this nft with proper amount of ether.
* After that the ERC20 tokens can be redeemable and one can get ether to their account after he/she redeems.
