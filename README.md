# Metacraft-Assesment
This repository contains the Solidity smart contract for my MetaCraft assessment. The smart contract implements a basic token system with functionalities for minting and burning tokens.
# Details
1. **Public Variables**:
* TokenName: Stores the name of the token.
* TokenAbbrv: Stores the abbreviation of the token.
* TotalSupply: Stores the total supply of the token.

2. **Mapping**:
* balances: Maps addresses to their corresponding token balances.

3. **Functions**:
* mint(address, value): Increases the total supply by the specified value and increases the balance of the specified address.
* burn(address, value): Decreases the total supply by the specified value and decreases the balance of the specified address.
 This function includes conditionals to ensure the balance of the account is greater than or equal to the amount to be burned.
# Getting Started
### Executing Program
1. To run this program, go to the Remix website at https://remix.ethereum.org/.
2. Create a new file.
3. Write the code.
# Author
Riya Verma
# License
This project is licensed under the MIT License - see the LICENSE.md file for details
