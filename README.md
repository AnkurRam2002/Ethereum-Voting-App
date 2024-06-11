<h1 align='center'> Ethereum Voting App </h1>
This project is a decentralized voting application built using the Ethereum blockchain. It leverages Web3.js, Truffle, Ganache, and MetaMask to provide a secure and transparent voting system with a user-friendly interface built with Bootstrap. 

<h3> Features </h3>

- Decentralized Voting: Secure and transparent voting on the Ethereum blockchain.
- Smart Contracts: Utilize Ethereum smart contracts for managing votes.
- MetaMask Integration: Users can connect their MetaMask wallets to participate in voting.
- Truffle Framework: Develop, test, and deploy smart contracts.
- Ganache: Local blockchain for development and testing.

<h3> Technologies Used </h3>

- Ethereum: Blockchain platform for decentralized applications.
- Solidity: Programming language for writing smart contracts.
- Truffle: Development framework for Ethereum.
- Ganache: Personal Ethereum blockchain for development.
- Web3.js: JavaScript library for interacting with the Ethereum blockchain.
- MetaMask: Browser extension for interacting with Ethereum.
- Bootstrap: CSS framework for responsive and mobile-first web development.
- JavaScript/HTML/CSS: Frontend technologies for building the user interface.

<h3> Installation </h3>

- Clone the repository:
```bash
git clone https://github.com/your-username/ethereum-voting-app.git
```

- Navigate to the project directory:
```bash
cd ethereum-voting-app
```

- Install Truffle globally if you haven't already:
```bash
npm install -g truffle
```

- Install dependencies:
```bash
npm install
```

- Start Ganache:
  - Open Ganache and create a new workspace.
  - Copy the RPC server address (usually http://127.0.0.1:7545).

- Compile and migrate the smart contracts:
```bash
truffle compile
truffle migrate
```

- Start the development server:
```bash
npm run start
```

- Open your web browser and visit http://localhost:3000 to view the application.

<h3> Usage </h3>

- Ensure MetaMask is installed in your web browser.
- Connect MetaMask to the Ganache local blockchain by adding a custom RPC network with the Ganache RPC server address.
- Import one of the Ganache accounts into MetaMask using the private key.
- Open the application and participate in the voting process.

<h3> Smart Contract Details </h3>

- Voting.sol: Solidity smart contract that manages the voting process.
- Migration.sol: Solidity contract used by Truffle for migrations.

<h3> Screenshots </h3>

<h3> Contributing </h3>
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch (git checkout -b feature/new-feature).
- Make your changes.
- Commit your changes (git commit -am 'Add new feature').
- Push to the branch (git push origin feature/new-feature).
- Create a new Pull Request.
  
<h3> License </h3>
This project is licensed under the MIT License - see the LICENSE file for details.


