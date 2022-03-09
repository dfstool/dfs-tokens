## How to add a token?

Make a pull request with the following changes:

1. Add metadata to [`tokens.json`](tokens.json)

```json
{
    "name": "<NAME>",
    "symbol": "<SYMBOL>",
    "contract": "<CONTRACT NAME>",
    "chain": "eos",
    "precision": 4
}
```

2. Add token logo to `./logos/$chain/$contract-$symbol.png`, 
add large token logo to `./logos/$chain/$contract-$symbol-large.png`

Next, you can splice to get the token logo you need. 
For example: https://raw.githubusercontent.com/metahubwallet/eos-tokens/master/logos/eos/tethertether-usdt.png, 
and CDN url: https://cdn.jsdelivr.net/gh/metahubwallet/eos-tokens@master/logos/eos/tethertether-usdt.png