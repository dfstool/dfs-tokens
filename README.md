## How to add a token?

Make a pull request with the following changes:

1. Add metadata to [`tokens.json`](tokens.json)

```json
{
    "name": "<NAME>",
    "symbol": "<SYMBOL>",
    "contract": "<CONTRACT NAME>",
    "chain": "dfs",
    "precision": 8
}
```

2. Add token logo to `./logos/$chain/$contract-$symbol.png`, 
add large token logo to `./logos/$chain/$contract-$symbol-large.png`

Next, you can splice to get the token logo you need. 
For example: https://raw.githubusercontent.com/dfstool/dfs-tokens/master/logos/dfs/tethertether-usdt.png
