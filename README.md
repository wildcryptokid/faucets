# faucets
Faucets for cryptocurrency chains

# where is data located
Data is located in specific folders, for evm chains in `evm` folder

# example of configuration found in `evm/11155111.json`
```
{
    "name": "Sepolia",
    "title": "Ethereum Testnet Sepolia",
    "chain": "Ethereum",
    "rpc": [
        "https://ethereum-sepolia-rpc.publicnode.com"
    ],
    "faucets": [
        {
            "name": "google cloud eth sepolia faucet",
            "url": "https://cloud.google.com/application/web3/faucet/ethereum/sepolia",
            "requirements": "google email account",
            "limits": [
                "0.05 sepolia testnet ETH",
                "Each Google Account and wallet address gets one drip on Sepolia every 1 day."
            ]
        }
    ],
    "native_currency": {
        "name": "sepolia testnet ETH",
        "symbol": "ETH",
        "decimals": 18
    },
    "info_url": "https://sepolia.etherscan.io",
    "chain_id": 11155111,
    "network_id": 11155111,
    "explorers": [
        {
            "name": "etherscan-sepolia",
            "url": "https://sepolia.etherscan.io"
        }
    ]
}
```

# usages
## other
 * [WildCryptoKid](https://wildcryptokid.com/)
   
 * Your project - contact us to add it here!
