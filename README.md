# Project Title

ERC20 Contract

## Description

This is an ERC20 token contract that enables token creation, where only the contract owner has the authority to mint tokens, while any user can transfer and burn them.

- State: Maintains an owner state variable that stores the contract owner's address.
- Modifiers: Includes two modifiers:
    - onlyOwner: Ensures that only the contract owner (msg.sender) can perform certain actions.
    - checkTokenBalance: Verifies that an address has a sufficient token balance before executing specific functions.
- Functions: The contract provides functions for minting, burning and transferring tokens.


## Getting Started

### Executing program
For ease in executing the smart contract, 
the can be copied and use in remix environment to 
interact with different functions in the contract

## Authors

Contributors names and contact info

ex. toyin


## License

This project is licensed under the MIT License 