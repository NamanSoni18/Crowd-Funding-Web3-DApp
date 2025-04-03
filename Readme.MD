# Web3 Crowdfunding DApp

![ThirdWeb](https://img.shields.io/badge/thirdweb-black?style=for-the-badge&logo=thirdweb&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)

A decentralized crowdfunding platform built with thirdweb that allows users to create and fund campaigns on the blockchain.

## 📁 Project Structure
```bash
web3-crowdfunding/
├── web3appcontract/ # Smart contract code
│ ├── contracts/ # Solidity files
│ ├── scripts/ # Deployment scripts
│ └── test/ # Test files
│
└── web3crowdfunding/ # Frontend application
├── components/ # React components
├── src/ # Next.js pages
└── utils/ # Utility functions
```

## ⚙️ Setup
### Prerequisites
- Node.js v16+
- Yarn
- ThirdWeb account
- MetaMask wallet

### Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/web3-crowdfunding.git
```
Install dependencies for both folders:

```bash
cd web3-crowdfunding/web3crowdfunding
yarn install
```

Set up environment variables:
```bash
# In web3crowdfunding/.env.local
NEXT_PUBLIC_TEMPLATE_CLIENT_ID=your_thirdweb_client_id
NEXT_PUBLIC_CONTRACT_ADDRESS=your_contract_address
```


🏃‍♂️ Running Locally
```bash
cd web3crowdfunding
yarn dev
```
Open http://localhost:3000 in your browser


🛠️ Deployment
Smart Contract
Deployed via ThirdWeb dashboard or CLI:
```bash
npx thirdweb deploy
```

Frontend
Deployed on ThirdWeb hosting:
```bash
yarn build
npx thirdweb deploy
```

✨ Features
Create campaigns with name, description, goal, and deadline

📜 License
MIT License