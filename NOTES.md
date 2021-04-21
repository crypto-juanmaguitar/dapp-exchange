
**Deploy contracts**

To deploy the smart contracts we can do 

```sh
truffle migrate --reset
```

The `--reset` forces a new deploy even if `abi` files already exists

**Feed the contracts with data**

```sh
truffle exec scripts/seed-exchange.js
```






