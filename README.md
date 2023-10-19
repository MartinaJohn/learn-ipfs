# learn-ipfs

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_URL` = "https://volta-rpc.energyweb.org/"

`PRIVATE_KEY`=> private key of the account where volta tokens are imported

`CONTRACT_ADDRESS`

## Installation

```bash
  npm i
  npx hardhat init
  npx hardhat compile
  npx hardhat run --network volta scripts/deploy.js
  node index.js
```
