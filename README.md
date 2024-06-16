Here's the revised README template for your repository "NSC.INC-patent" in English, reflecting the founder's name "Lucas Januario do Nascimento" and including details such as a Smart Contract for patent registration:

---

# NSC.INC Patent Repository

This repository contains a Solidity smart contract designed for registering basic company details on the Ethereum blockchain, specifically tailored for patent registration. The contract allows registration of information such as company name, registration number, address, founder, and role, utilizing Solidity language and the Ethereum platform.

## Contract Structure

The contract includes a basic structure to store the following company data:

- **Company Name**
- **Registration Number**
- **Company Address**
- **Founder**
- **Role in the Company**
- **Contract Owner**

The contract is designed to be straightforward and can be expanded with additional functionality as needed.

## Features

1. **Company Registration**: Upon deploying the contract, the company's data is automatically set on the Ethereum blockchain.

2. **Data Viewing**: Anyone can view the registered company details using the `getCompanyDetails` function.

## Founder

- **Lucas Januario do Nascimento**, Brazil

## How to Use

### Prerequisites

- Basic knowledge of smart contracts and Solidity.
- Access to an Ethereum wallet with Ether to cover transaction fees.

### Deployment

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/NSC.INC-patent.git
   ```

2. Navigate to the project directory:

   ```bash
   cd NSC.INC-patent
   ```

3. Compile the smart contract using Remix or another tool of your choice.

4. Configure your Ethereum wallet (e.g., MetaMask) for the desired network (Mainnet, Ropsten, etc.).

5. Deploy the contract using tools like Remix Ethereum IDE or Truffle, providing desired parameters (adjust the contract constructor in `CompanyRegistration.sol` file if necessary).

6. After deployment, you can call the `getCompanyDetails` function to view the registered company details.

## Contributions

Contributions are welcome! Feel free to submit pull requests with improvements, fixes, or additional features for the smart contract.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](./LICENSE) file for more details.

---

This README provides a clear overview of the project, explains how to use the smart contract, and invites other developers to contribute to the project. Make sure to customize the README with specific information about your project and adjust it as needed.
