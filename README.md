# Functions-and-Errors
ETH + AVAX PROOF: Intermediate EVM Course | Functions and Errors - ETH + AVAX

This Solidity contract, named `modOne`, serves as an illustrative example showcasing the use of `require()`, `assert()`, and `revert()` statements for various validation scenarios. The contract includes a `modifier` named `onlyOwner` to restrict certain functions exclusively to the contract owner.

## Contract Details

**Owner:** The contract is initialized with an owner address, and only the owner can execute specific actions.

### Functions:

1. **placeBet(uint256 _newValue):** Allows the owner to set a new value, requiring the input to be greater than zero.

2. **validateBetSum(uint256 a, uint256 b):** Validates the sum of two inputs using the `assert()` statement, ensuring it equals 50.

3. **validateBet(uint256 input):** Validates the input using `require()` and includes a `revert()` statement if the input is greater than 100.

## Usage

1. Deploy the contract by compiling and deploying the `modOne` Solidity contract using tools such as Remix, Truffle, or Hardhat.

2. Interact with the contract, keeping in mind the restrictions imposed by the `onlyOwner` modifier.

