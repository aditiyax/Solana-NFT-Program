
# Solana NFT Program

Welcome to the Solana NFT Program! This smart contract lets you mint, transfer, and manage NFTs on the Solana blockchain using the Anchor framework. 

## 🚀 Quick Setup

### Requirements

- Rust & Cargo
- Solana CLI
- Node.js & Yarn
- Anchor CLI

### Installation

1. **Clone the Repo**:
   \`\`\`bash
   git clone https://github.com/aditiyax/Solana-NFT-Program.git
   cd Solana-NFT-program
   \`\`\`

2. **Install Dependencies**:
   \`\`\`bash
   yarn install
   \`\`\`

3. **Build the Program**:
   \`\`\`bash
   anchor build
   \`\`\`

4. **Deploy the Program**:
   \`\`\`bash
   anchor deploy
   \`\`\`

## 📜 Program Overview

### Features

- **Mint NFTs**: Create new, unique tokens.
- **Transfer NFTs**: Send NFTs to other users.
- **Burn NFTs**: Remove NFTs from circulation.
- **Manage Metadata**: Attach and update details like name, description, and URI.

### Core Functions

- \`initialize_nft\`: Set up a new NFT.
- \`mint_nft\`: Mint a token and assign it to an account.
- \`transfer_nft\`: Move NFTs between accounts.
- \`burn_nft\`: Destroy an NFT.

### Account Structure

- **Mint Account**: The source of NFTs.
- **Token Account**: Holds your NFTs.
- **Metadata Account**: Stores details like name, URI, etc.

## ⚙️ Testing

1. **Start a Local Validator**:
   \`\`\`bash
   solana-test-validator
   \`\`\`

2. **Run Tests**:
   \`\`\`bash
   anchor test
   \`\`\`


## 📄 License

This project is under the MIT License—see \`LICENSE\` for details.


---

Start minting your own NFTs on Solana today! 🚀


Solana explorer link: https://explorer.solana.com/address/DgfMRAseqGCjXgxWbXYFFfKsEfamAav7kRtMs5pdED1q?cluster=devnet
