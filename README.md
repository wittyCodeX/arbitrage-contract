# Simple Dex Arbitrage

```shell
https://github.com/ethancrypto/arbitrage-contract.git
cd DEX-Arbitrage
mv .env-example.txt .env
npm install
npx hardhat run --network bsc .\scripts\deploy.js
```

Then add the arbContract deployment address to config/aurora.json edit the base assets and move the funds across to the the arbContract address.

Then to execute run:-

```shell
npx hardhat run --network bsc .\scripts\deploy.js
```

Finally to recover any funds use the script.

```shell
npx hardhat run --network bsc .\scripts\recover.js
```
