# EthToken - Basic Ethereum Token Contract

EthToken is a simple Ethereum token contract (ERC-20) with mint and burn functions. It allows token creation (`mint`) for an address and token destruction (`burn`) based on balance checks.

## Functions

1. `mint(address _address, uint _value)`: Creates new tokens for the given address and increases total supply accordingly.

2. `burn(address _address, uint _value)`: Destroys tokens for the specified address, reducing total supply, with a balance check to prevent burning more than available.

## Usage

This contract provides a foundation for managing a basic token on the Ethereum blockchain. To deploy the contract, you can use Solidity version 0.8.19 or compatible versions.

1. Set the desired token name, abbreviation, and initial total supply in the contract.

2. Deploy the contract to the Ethereum blockchain.

3. Interact with the contract by calling the `mint` function to create new tokens for specific addresses and the `burn` function to destroy existing tokens.

**Note:** Exercise caution when deploying and testing on the mainnet, and consider additional features to enhance security and usability.

## License

This project is licensed under the MIT License.
