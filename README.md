# Metacrafters Solidty Assessment

This Solidity program is a simple program that allows minting and burning of tokens. This program was created as part of the assessment for Metacrafter's ETH Proof: Beginner EVM Course in order to explore the syntax and functionalities of the Solidity programming language.

## Description

This is a simple Solidity smart contract for a custom token named NOAH (NOA). The contract allows for the minting and burning of tokens, with public variables to track the token's details and total supply. The token management is done through the functions provided within the contract.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

* First, download the [SolidityAssessment.sol](SolidityAssessment.sol) file found in this repository.
* On the Remix website, click "Open a File from your File System" in the left-hand sidebar and open the file you've downloaded.
* To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.26" (or another compatible version), and then click on the "Compile SolidityAssessment.sol" button.
* Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "SolidityAssessment" contract from the dropdown menu, and then click on the "Deploy" button.
* Once the contract is deployed, you can interact with it by using the mint and burn functionalities. To mint tokens, click on the "MyToken" contract in the left-hand sidebar, select the mintToken function, input the desired address and the amount of tokens to mint, then click the "transact" button. This will increase the total supply and the balance of the specified address. To burn tokens, select the burnToken function, input the address and the amount of tokens to burn, and click "transact" to reduce the total supply and the balance of that address, provided the balance is sufficient.

## Authors

[@noawhaha](https://github.com/noooooahh)
