# EVM-based Chains

Listed by chainId according to EIP-155

Data source available on `_data/chains.json`

## Example

```json
{
  "name": "Ethereum Mainnet",
  "chain": "ETH",
  "network": "mainnet",
  "rpc": [
    "https://mainnet.infura.io/v3/${INFURA_API_KEY}",
    "https://api.mycryptoapi.com/eth"
  ],
  "faucets": [],
  "nativeCurrency": {
    "name": "Ether",
    "symbol": "ETH",
    "decimals": 18
  },
  "infoURL": "https://ethereum.org",
  "shortName": "eth",
  "chainId": 1,
  "networkId": 1
}
```

## Scripts

1. Install dependencies

```sh
cd scripts && npm install
```

2. Verify chainId and networkId

```sh
node scripts/verify.js
```