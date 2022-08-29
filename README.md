```

1. Using openZeppelin  standard create an erc20 token that mint to the contract address
2. Create a function that allows you to transfer the token  from the contract any other person.
3. Any address who owns token should trigger the Approve function in order to approve someone else to spend his token.

4.  the spender that is given approval in (3)  should be able to call the transferfrom function in order to spend the allowance given to him.

Compile, deploy and test using remix



```

# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
GAS_REPORT=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```
