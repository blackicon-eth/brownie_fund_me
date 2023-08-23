# brownie_fund_me
This is my very first Smart Contract. I made this by following a tutorial made by freeCodeCamp.org.
Through the lesson I learned how to deploy a contract using the brownie framework, how to retrieve price feeds from Chainlink and how to deploy a mock price feed contract in case of local testing.

This contract allows the user to deposit and withdraw funds by calling the right functions.
If you're the contract owner you can call a special functions that withdraws the total balance inside the contract itself.
The minimum funding amount is 50 USD, calculated in ether quantity. If you transaction's value is less than expected, it will be reverted.