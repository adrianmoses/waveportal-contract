# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```


Deploy steps

**you need to do this every time you change your contracts code**

1. Run `npx hardhat run scripts/deploy.js --network rinkeby`
2. Change contractAddress in App.js to be the new contract address we got from the step above in the terminal
3. Get the updated abi file from `artifacts/contracts/WavePortal.sol/WavePortal.json` like we did before and copy-paste it into Replit 

