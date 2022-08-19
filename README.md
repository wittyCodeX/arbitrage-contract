# Multi Dex Arbitrage

```shell
https://github.com/ethancrypto/arbitrage-contract.git
cd DEX-Arbitrage
mv .env-example.txt .env
npm install
npx hardhat run --network bsc .\scripts\deploy.js
```
Then copy the contract address into notepad. It will be used in backend server

Then to execute run:-

```shell
npx hardhat run --network bsc .\scripts\deploy.js
```

Finally to recover any funds use the script.

```shell
npx hardhat run --network bsc .\scripts\recover.js
```

#Verify contract
$ npx hardhat  verify --network bsc 0x9b45ceD85f1DD3F7C1E1037e373F6E22eB687A1C
