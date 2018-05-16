# The "TutorialToken" Smart Contract With OpenZeppelin

You can find complete tutorial of this smart contract [here](http://truffleframework.com/tutorials/robust-smart-contracts-with-openzeppelin).

# Building robust smart contracts with OpenZeppelin

Smart contracts deployed to the Ethereum mainnet can deal with real money, so having our Solidity code free from errors and highly secure is essential.

[Zeppelin Solutions](https://zeppelin.solutions/), a smart contract auditing service, has recognized this need. Using their experience, they've put together a set of vetted smart contracts called [OpenZeppelin](https://openzeppelin.org/).

We can use and extend these contracts to create more secure dapps in less time. OpenZeppelin comes with a wide array of smart contracts for various important functions (see them all here), but today we'll be focusing on their token contracts. Specifically, we'll be extending their StandardToken.sol contract to create our own ERC20-compliant token.

# Environment

$ node -v v8.11.1

$ npm -v 5.6.0

$ truffle version

Truffle v4.1.8 (core: 4.1.8)

Solidity v0.4.23 (solc-js)

$ # Ganache

$ # MetMask version: 4.6.1

# Instructions:

1.  Download the complete repository and go to the folder in your terminal

2.  Run the development console.

         truffle develop

3.  Compile and migrate the smart contracts. Note inside the development console we don't preface commands with truffle.

         compile
         migrate

4.  Open another ternminal and Run the liteserver development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.

    // Serves the front-end on http://localhost:3000

         npm run dev
