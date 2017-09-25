# testrpc_usage

1. unlock account, precondition: testrpc is not started<br>
```$ testrpc --secure -u 0 -u 1 ...```

2. start testrpc with number of accounts to create<br>
```$ testrpc -a 10```

3. get network ID<br>
```$ curl -X POST --data '{"jsonrpc":"2.0","method":"net_version","params":[]}' http://localhost:8545```

https://github.com/ethereumjs/testrpc
