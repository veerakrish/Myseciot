# Blank Smart Contract Template BBN Testnet

This workspace contains 3 directories:

1. 'contracts': Holds one storage contract.
2. 'scripts': Contains four typescript files to deploy a contract. It is explained below.
3. 'tests': Contains one Solidity test file for 'Ballot' contract & one JS test file for 'Storage' contract.


# 1. Project Setup

```shell
npm install

```
# 2. Create a new .env file and write below configuration
PRIVATE_KEY = "YOUR_PRIVATE_KEY"
CONTRACT_ADDRESS = "YOUR_CONTRACT_ADDRESS"
RPC_NODE_URL = "https://idspeer1.test.bharatblockchain.io:15021"

# 3. Smart Contract Compile

```shell
npx hardhat compile
```

# 4. Deploy the Smart Contract
```shell
npx hardhat run ./scripts/deploy.ts --network bbn_testnet
```
 
# 5. Update the deployed smart contract address in .env file from deployedAddresses.json file.


# 6. Interact with Smart Contract

# Write functions and a script file named interact.ts

```shell
npx hardhat run ./scripts/interact.ts --network bbn_testnet
```

# 7. Check your txs on BBN Testnet Explorer

https://testnet.bharatblockchain.io/


