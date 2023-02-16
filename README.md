# EVM web3 hook

## How to use

1. Wrap the top level <App/> component by <Web3Provider>

```
import Web3Provider from "evm-web3-hook";

<Web3Provider>
  <App/>
</Web3Provider>
```

2. Use global web3Context everywhere

```
const web3Context = useWeb3()
```

3. The example [EVM Dapp boilerplate](https://github.com/happyeric77/evm-dapp-boilerplate-ts.git)
