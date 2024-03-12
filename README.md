# juno-kit

This is a toolkit from juno transfer and query balance.

## functions

- query balance from juno chain and transfer it

```
import {queryBalance,transfer} from 'juno-kit';

const taskquery = async ()=>{
  const balance = await queryBalance(mnemonic,0,juno_rpc);
  console.log(balance);
}

const tasktransfer = async ()=>{
  const result = await transfer(mnemonic,from,to,amount,customgas,rpc);
  console.log(result);
}

```
