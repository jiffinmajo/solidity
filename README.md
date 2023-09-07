# Solidity
Here we gonna create a simple Solidity smart contract for creating a custom ERC-20 token called "DEXA" (DXA)
## Contract Details
- *Token Name*: DEXA
- *Token Abbreviation*: DXA
- *Total Supply*: 0 (initially)
# Public variables
We are getting started with assigning the name and abbrevation of the token we are gonna create
- `tokenName`: A public string variable representing the name of the token.
- `tokenAbbrv`: A public string variable representing the abbreviation of the token (symbol).
- `totalSupply`: A public unsigned integer variable representing the total supply of the token.
# Mapping variable
balances: A mapping that associates addresses with their corresponding token balances. It tracks the number of tokens held by each address.
# Functions
# Mint function
This function allows the contract owner (or anyone with the appropriate permissions) to mint new tokens and assign them to a specific address.
- Parameters:
  - `_address`: The address to which the newly minted tokens will be assigned.
  - `_value`: The number of tokens to mint and assign.
# Burn function
The `burn` function allows the contract owner (or anyone with the appropriate permissions) to burn a specific number of tokens held by a given address.
- Parameters:
  - `_address`: The address from which tokens will be burned.
  - `_value`: The number of tokens to burn.
Please note that burning tokens reduces the total supply of the token, and it can only be executed if the balance of the target address is equal to or greater than the number of tokens to be burned.

## License

This smart contract is licensed under the MIT License.

#Author
Jiffin Majo
