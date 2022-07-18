# Flow NFT Starter Kit

Flow NFT Starter Kit from buildspace

## Deploy

```sh
# send transaction to local testnet
flow transactions send ./transactions/mintNFT.cdc "0xf8d6e0586b0a20c7" "CatMoji #1" "Cat emojis on the blockchain" "ipfs://bafybeigmeykxsur4ya2p3nw6r7hz2kp3r2clhvzwiqaashhz5efhewkkgu/0.png"

# deploy to testnet
flow project deploy --network testnet
```
