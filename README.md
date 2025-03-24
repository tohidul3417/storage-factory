# Storage Factory

This project is part of the **"Solidity Smart Contract Development"** course in **Cyfrin Updraft**. It implements a **Storage Factory** that dynamically deploys multiple instances of a simple storage contract and interacts with them.

## Overview
The project consists of three Solidity smart contracts:

1. **SimpleStorage.sol** – A basic contract that allows storing, retrieving, and mapping favorite numbers to names.
2. **StorageFactory.sol** – A factory contract that creates multiple instances of `SimpleStorage` and interacts with them.
3. **AddFiveStorage.sol** – A modified version of `SimpleStorage` that adds 5 to any stored number.

## Smart Contracts
### SimpleStorage.sol
- Stores a single `uint256` value.
- Supports retrieving the stored value.
- Maps names to favorite numbers.

### StorageFactory.sol
- Deploys new instances of `SimpleStorage`.
- Keeps track of deployed contracts.
- Allows interaction with deployed contracts by index.

### AddFiveStorage.sol
- Inherits from `SimpleStorage`.
- Overrides the `store()` function to add 5 before saving the number.

## License
This project is licensed under the **MIT License**.
