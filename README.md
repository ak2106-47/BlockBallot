
# BlockBallot: A Decentralized Voting System

BlockBallot is a one-of-a-kind decentralized voting system built on the Solana blockchain. It provides a secure, transparent, and efficient platform for conducting polls and elections.

## Features

- **Decentralized**: Leverages Solana blockchain for transparent and tamper-proof voting.
- **User-friendly Interface**: Easy-to-use web application for creating and participating in polls.
- **Secure**: Utilizes blockchain technology to ensure vote integrity and prevent fraud.
- **Real-time Results**: View poll results as they come in.
- **Customizable Polls**: Create polls with multiple options and custom durations.

## User Interface



https://github.com/user-attachments/assets/7c82994c-7b16-43ea-9a18-1f754bcb536d


## Getting Started

### Prerequisites

- Node.js (v14 or later)
- Yarn package manager
- Solana CLI tools
- A Solana wallet (e.g., Phantom Wallet)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ak2106-47/BlockBallot.git
cd BlockBallot
```
2. Install dependencies:
```bash
yarn install
```
3. Generate a New Wallet:
```bash
solana-keygen new -o id.json
```
4. Airdrop SOL into Wallet:
```bash
solana airdrop 4 <publicKey> --url devnet
```
5. Build the Anchor Project:
```bash
anchor build
```
6. Get Program ID:
```bash
solana address -k ./target/deploy/BlockBallot.json
```
7. Deploy the Anchor Program:
```bash
anchor deploy
```
8. Start the development server:
```bash
yarn dev
```

9. Open your browser and navigate to `http://localhost:3000` to view the application.

### Usage

1. Connect your Solana wallet to the application.
2. To create a poll, click on "Create Poll" and follow the prompts.
3. To vote in an existing poll, enter the poll code and select your choice.
4. View real-time results after voting.


## Technologies Used

- **Frontend**:
  - React.js
  - Tailwind CSS for styling
  - react-router-dom for routing

- **Blockchain**:
  - Solana blockchain
  - @solana/web3.js for Solana interactions
  - @project-serum/anchor for smart contract interactions

- **Wallet Integration**:
  - @solana/wallet-adapter for connecting to Solana wallets

- **Build Tools**:
  - Create React App
  - Webpack

- **Version Control**:
  - Git & GitHub


## Contributing

I would gladly welcome contributions from the community, especially those that enhance its blockchain capabilities. Feel free to fork the repository, make your improvements, and submit a pull request.


## License

This project is licensed under the Apache-2.0 license - see the [LICENSE](LICENSE) file for details.

## Acknowledgment

- Heartfelt thanks to all who visit and engage with BlockBallot. Your interest, usage, and feedback are the driving forces behind our continuous improvement and innovation. I am  committed to delivering value and enhancing your financial management experience, inspired by your support and insights.









