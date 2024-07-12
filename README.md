# ERC20 Token Implementation

This Solidity program implements the ERC20 token standard, providing a template for creating fungible tokens on the Ethereum blockchain. It demonstrates the core functionality of ERC20 tokens and serves as a foundation for more complex token implementations.

## Description

This program is a contract written in Solidity that implements the ERC20 interface. It includes all standard ERC20 functions such as transfer, approve, transferFrom, as well as additional utility functions like increaseAllowance and decreaseAllowance. The contract also implements basic token information like name, symbol, and decimals.

Key features of this implementation:
- Standard ERC20 functionality
- Additional allowance management functions
- Minting and burning capabilities (internal functions)
- Hooks for extending functionality
- Comprehensive error handling and requirements

This implementation can be used as a starting point for creating custom tokens or as a learning resource for understanding ERC20 token mechanics.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., ERC20Token.sol). Copy and paste the provided code into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.0" (or another compatible version), and then click on the "Compile ERC20Token.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "ERC20" contract from the dropdown menu, and then click on the "Deploy" button.

After deployment, you can interact with the contract by calling its various functions like transfer, approve, balanceOf, etc.

## Authors

Gitanjali  
Email: gitanjali.e116525@cumail.in

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
