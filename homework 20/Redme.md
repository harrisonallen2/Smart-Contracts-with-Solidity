# **Unit 20 - "Looks like we've made our First Contract!"**
![](Aspose.Words.d0466c44-8672-46e1-a0e1-999df4df3211.001.png)

Background

Your new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic.

Fortunately, you've been learning how to program smart contracts with Solidity! What you will be doing this assignment is creating 3 ProfitSplitter contracts. These contracts will do several things:

- Pay your associate-level employees quickly and easily.

Instructions

- Level One is an AssociateProfitSplitter contract. This will accept ether into the contract, and divide it evenly among associate-level employees. This will allow the human resources department to pay employees quickly and efficiently.

Starting your project

Navigate to the Remix IDE and create a new contract called AssociateProfitSplitter.sol using the starter code for Level One.

While developing and testing your contract, use the Ganache development chain, and point MetaMask to localhost:8545, or replace the port with what you have set in your workspace.

Level One: The AssociateProfitSplitter Contract

1. Define public variables;
1. Create a constructor function;
1. Within the constructor, set the employee addresses to equal the parameter values. This will allow you to avoid hardcoding the employee addresses.
1. Next, create the following functions: BALANCE AND DEPOSIT;
1. Create a fallback function using function() external payable, and call the deposit function from within it. This will ensure that the logic in deposit executes if ether is sent directly to the contract. This is important to prevent ether from being locked in the contract, since we don't have a withdraw function in this use case.

Test the contract

In the Deploy tab in Remix, deploy the contract to your local Ganache chain by connecting to Injected Web3 and ensuring MetaMask is pointed to localhost:8545.

![](Aspose.Words.d0466c44-8672-46e1-a0e1-999df4df3211.002.png)

![](Aspose.Words.d0466c44-8672-46e1-a0e1-999df4df3211.003.png)

You will need to fill in the constructor parameters with your designated employee addresses.

![](Aspose.Words.d0466c44-8672-46e1-a0e1-999df4df3211.004.png)

![](Aspose.Words.d0466c44-8672-46e1-a0e1-999df4df3211.005.png)

Test the deposit function by sending various values. Keep an eye on the employee balances as you send different amounts of ether to the contract and ensure the logic is executing properly.

![](Aspose.Words.d0466c44-8672-46e1-a0e1-999df4df3211.006.png)

![](Aspose.Words.d0466c44-8672-46e1-a0e1-999df4df3211.004.png)

Resources

Building the next financial revolution isn't easy, but we need your help. Don't be intimidated by the semicolons!

There are lots of great resources to learn Solidity. Remember, you are helping push the very edge of this space forward, so don't feel discouraged if you get stuck! In fact, be proud that you are taking on such a challenge!

For some succinct and straightforward code snips, check out [Solidity By Example](https://github.com/raineorshine/solidity-by-example)

For a more extensive list of awesome Solidity resources, check out [Awesome Solidity](https://github.com/bkrem/awesome-solidity)

Another tutorial is available at [EthereumDev.io](https://ethereumdev.io/)

If you enjoy building games, here's an excellent tutorial called [CryptoZombies](https://cryptozombies.io/)

