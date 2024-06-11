# My Assessment Token

## Introduction

This Solidity contract implements a simple token system to store student marks details. It provides basic functionalities to mint(add marks) and burn (deduct marks) tokens representing student marks.

## Requirements

1. **Token Details:** The contract stores information about the token, including its name, abbreviation (here it is used in form of student uid), and total supply (here it refers to the total or Maximum Marks a student get get).
2. **Balances:** It maintains a mapping of addresses to token balances.
3. **Mint Function:** A function to increase the total supply and add tokens to the balance of a specified address.
4. **Burn Function:** A function to decrease the total supply and remove tokens from the balance of a specified address, with appropriate checks to ensure the address has enough tokens to burn.

## Public Variables

- `studentName`: Name of the student.
- `studentuid`: Student's unique identifier.
- `totalMarks`: Total marks accumulated.

## Functions

### `mint(address _Address, uint _Marks)`

Increments the total marks and adds `_Marks` to the balance of the specified `_Address`.

### `burn(address _Address, uint _Marks)`

Decreases the total marks and subtracts `_Marks` from the balance of the specified `_Address`, provided the address has sufficient balance.

## Usage

1. Deploy the contract to a supported Ethereum Virtual Machine (EVM) network.
2. Call the `mint` function to add marks to a student's balance.
3. Call the `burn` function to subtract marks from a student's balance.

## Code Execution
Once the code is compiled, deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyassessmentToken" contract from the dropdown menu, and then click on the "Deploy" button.
Once the contract is deployed, you can interact with it by calling the mint and burn functions. Click on the "MyassessmentToken" contract in the left-hand sidebar, and then click on the mint function. Enter the address and the totalmarks. Finally, click on the "transact" button to execute the function.
Repeat the same with the burn function for updating the totalMarks when required.

## Video Tutorial

[Watch video](https://www.loom.com/share/4d7aef283e6a46439040fb4e0be3e980?sid=7c9530bd-be76-4d49-9ce9-da5a954762eb): Another tutorial video providing additional guidance.


## Author

This project is made by Udit, B.tech Student at Chandigarh University

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
