# Smart contract application "Fund me"

## Scripts

### 1. Deploy

```
brownie run scripts/deploy.py
```

### 2. Fund and withdraw

```
brownie run scripts/fund_and_withdraw.py
```

## Run tests

```
brownie test
```

## Networks

1. Development - default
2. ganache-local - with local ganache
3. mainnet-fork-dev - fork from mainnet (need to add it to brownie)

```
brownie networks add development mainnet-fork-dev cmd=ganache-cli host=http://127.0.0.1 fork='https://mainnet.infura.io/v3/$WEB3_INFURA_PROJECT_ID' accounts=10 mnemonic=brownie port=8545
```

4. Rinkeby - persistent network
