# Hello World Solidity Program

## Description
This Solidity program serves as a simple "Hello World" example to demonstrate the basic syntax and functionality of the Solidity programming language. It is designed for individuals who are new to Solidity and wish to gain familiarity with its structure and usage. The program consists of a single contract with a function that returns the string "Hello World!". It can be used as a starting point for learning Solidity and as a foundation for more complex smart contract development.

## Getting Started
### Executing Program
To run this program, you can use Remix, an online Solidity IDE. Follow these steps:
1. Go to the Remix website at [https://remix.ethereum.org/](https://remix.ethereum.org/).
2. Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol).
3. Copy and paste the following code into the file:

```solidity
pragma solidity ^0.8.4;

contract HelloWorld {
    function sayHello() public pure returns (string memory) {
        return "Hello World!";
    }
}
#Authors
Tayshaun Rala
@tayshaunrala@gmail.com

#License
This project is licensed under the MIT License - see the LICENSE.md file for details.
