**ERC20 and Vault Contracts README**

### Overview:

This repository contains two Solidity smart contracts: ERC20 and Vault. These contracts are designed to facilitate the creation and management of ERC20 tokens and a secure vault for storing those tokens.

### Contracts:

1. **ERC20.sol**:
   - This contract implements the ERC20 standard token functionality. It provides methods for transferring tokens, approving spending limits for other addresses, and querying token balances.

2. **Vault.sol**:
   - The Vault contract serves as a secure storage for ERC20 tokens. It allows authorized users to deposit and withdraw tokens. The Vault employs access controls to ensure only authorized parties can interact with it.

### Usage:

1. **Deploying Contracts**:
   - Deploy both ERC20 and Vault contracts to your Ethereum network of choice. Make sure to configure constructor parameters such as token name, symbol, and initial supply for ERC20 contract, and set appropriate access controls for the Vault contract.

2. **Interacting with ERC20**:
   - After deployment, users can interact with the ERC20 contract to transfer tokens, check balances, and approve spending limits for other addresses.

3. **Utilizing the Vault**:
   - Authorized users can deposit ERC20 tokens into the Vault and withdraw them as needed. Access controls ensure only permitted addresses can deposit or withdraw tokens.

### License:

This project is licensed under the [MIT License](LICENSE).
