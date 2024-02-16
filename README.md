# Token README

This repository contains a Solidity smart contract for creating and managing a basic ERC20 token on the Ethereum blockchain. The contract allows for minting, burning, and transferring tokens.

## Contract Overview

The `Token` contract inherits from several OpenZeppelin contracts:
- `ERC20`: Implements the ERC20 standard for fungible tokens.
- `ERC20Burnable`: Provides functionality to burn (destroy) tokens.
- `Ownable`: Allows for ownership control, ensuring that certain functions can only be executed by the contract owner.

The contract includes the following main functions:

1. **Constructor**: Initializes the token with a name and symbol.
2. **Minting Tokens**: Allows the contract owner to mint new tokens and assign them to a specified address.
3. **Burning Tokens**: Enables token holders to destroy a specified amount of their own tokens.
4. **Transferring Tokens**: Allows token holders to transfer tokens to other addresses.


## Contract Interactions

Once deployed, you can interact with the contract through various methods:

- **Minting Tokens**: Call the `mintTokens` function, specifying the address to receive the tokens and the total amount to mint.
- **Burning Tokens**: Call the `burnTokens` function, specifying the amount of tokens to burn.
- **Transferring Tokens**: Transfer tokens by calling the `transferTokens` function, providing the recipient's address and the amount of tokens to transfer.

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

