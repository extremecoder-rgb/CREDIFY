Credify

Credify is a blockchain-based academic credential system designed to securely manage and verify academic records. By leveraging decentralized technologies, Credify ensures data immutability, transparency, and accessibility while maintaining user privacy.

Features

Decentralized Credential Storage: Store academic credentials on IPFS for secure and distributed storage.

Blockchain Integration: Use Ethereum blockchain and smart contracts for immutable credential verification.

User-Friendly Interface: Built with HTML, CSS, and JavaScript for seamless interaction.

Secure Transactions: Utilize Metamask for secure authentication and transactions.

Tech Stack

Frontend:

HTML

CSS

JavaScript

Blockchain:

Solidity

Hardhat (development framework)

Storage:

IPFS (InterPlanetary File System)

Wallet Integration:

Metamask

Installation and Usage

Clone the Repository:

git clone https://github.com/extremecoder-rgb/CREDIFY.git
cd CREDIFY

Install Dependencies:

npm install

Compile Smart Contracts:

npx hardhat compile

Deploy Smart Contracts:

npx hardhat run scripts/deploy.js --network <network_name>

Start the Application:
Open the index.html file in your browser or host it on a local server.

How It Works

Credential Submission: Academic institutions or individuals upload credentials via the web interface.

IPFS Storage: Credentials are securely stored on IPFS, generating a unique hash.

Blockchain Verification: The IPFS hash is stored on the Ethereum blockchain for tamper-proof verification.

Access and Verify: Users can retrieve and verify credentials using their blockchain address.

Requirements

Node.js and npm

Metamask wallet extension

Hardhat development environment

Contributing

Contributions are welcome! Please fork the repository and submit a pull request with detailed changes.

License

This project is licensed under the MIT License. See the LICENSE file for details.

