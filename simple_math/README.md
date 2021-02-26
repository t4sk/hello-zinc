```shell
ADDRESS=0x84891993a9da584b05425d66f6fcc535c2c89a13

# Account ID 10523

# get storage
zargo query --network rinkeby --address $ADDRESS

# call deposit
zargo call --network rinkeby --address $ADDRESS --method deposit
```
