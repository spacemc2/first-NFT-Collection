# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
It has two main contracts, Whitelist and Crypto Dev. The first one creates a whitelist for the first 10 users requesting a Crypto Dev. It registers the address code
in order to give them that privilege for free. All users including the first 10 can buy the token for 0.01 once or multiple times until the contract reaches the limit of tokens. The Crypto Dev contract on the other hand allows you to mind money in exchange for the Crypto Dev Token, also if you are the owner you can withdraw the money collected to your account.
