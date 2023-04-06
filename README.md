# ShareX
ShareX aims to provide a platform allowing collateral-free NFTs renting and instalment plans. Our tagline, "Time To Rent" plays the core concept of the separation of usage rights and ownership. It will be a fully decentralized NFT marketplace. 

## Description 
Our platform implements the collateral-free renting and instalment payment by utilising the divided property rights feature of the 30th final ERC standard - ERC-4907, which provides a clear-cut definition for ownership and usage rights. In the context of collateral-free renting, it allows lenders to bear 0 risks of losing their original_NFT to the renters. Once renters rent an NFT, a rent_NFT will be minted to renters with an expiration date. Renters can never forcibly occupy the original_NFT because they do not have ownership from the start and their usage rights will be revoked automatically by the expires() function in the smart contract. As long as the original_NFT is not rented, lenders can always enjoy the usage rights or burn the voucher token to redeem their NFT. Our approach to instalment will be an extension to the previous steps, in which instalments can be considered as n-times-rental and lenders transfer the voucher token to buyers upon completion of the instalment.

## Techonologies Used
### Smart Contracts
- [ERC-4907](https://eips.ethereum.org/EIPS/eip-4907)
- [ERC-721](https://docs.openzeppelin.com/contracts/4.x/erc721)
- dapp frameworks
- Transaction protocols
- Solidity
- JavaScript
