```shell
zargo new --type contract contract_name
zargo build
zargo publish --network rinkeby --instance default

Address 0x92c79ce7b04bc6a5dcb7157f9a2bbe6b54d8d196
Account ID 7936

ADDRESS=0x92c79ce7b04bc6a5dcb7157f9a2bbe6b54d8d196

# get storage
zargo query --network rinkeby --address $ADDRESS
# call function
zargo query --network rinkeby --address $ADDRESS get_foo
```
