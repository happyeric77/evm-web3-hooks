# EVM web3 hook

## How to use

0. npm install package

```
yarn add evm-web3-hooks
//or
npm install evm-web3-hooks
```

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
