# Task - Payable

- Growic Solidity Developer Program

Smart contract that saves user balance.

This contract has function that allows users to send real ETH deposits to the contract saves the amount a user is depositing into a mapping and a function that searches for user balance inside the mapping and returns the balance of who calls the contract.

- The fallback() function will be executed when a user calls a function that does not exist and also when msg.data is not empty.

The fallback() function will also be called when Ether is sent to this contract and there is no receive() function.

- The receive() function will be executed when msg.data is empty
