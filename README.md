# solidity-hello-world

## Getting Started
1. Rename `.env.default` to `.env`
2. Update Alchemy API key and Ropsten wallet private key within `.env`
3. Run `npx hardhat compile` to ensure smart contract code is valid
4. Run `npx hardhat run scripts/deploy.js --network ropsten` to deploy the contract
5. Copy the contract address from the console and replace the `CONTACT_ADDRESS` value within `.env`
6. Run `npx hardhat run scripts/interact.js --network ropsten` to update the contract

## See
- https://www.youtube.com/watch?v=g73EGNKatDw
- https://www.youtube.com/watch?v=sQJ-XQBzEuc
- https://www.youtube.com/watch?v=x1a5lrW-9fo