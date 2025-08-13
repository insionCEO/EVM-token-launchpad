# 🚀 Pump.flawk 

A decentralized meme coin platform with a Next.js frontend and Ethereum smart contracts.  
🌟 Drop a ⭐️ if you dig the vibe!

- [Preview Link](https://pumpflawk.vercel.app/)

## ✨ Features  
- Interactive Linear bonding curve mechanics  
- Liquidity pool automation
- create Memecoin

## 🛠️ Tech Stack  
- **Frontend**: Next.js, TypeScript, Tailwind CSS, RainbowKIT SDK
- **Smart Contracts**: Solidity, Hardhat, Moralis
- **Deployment**: Vercel, Sepolia  

## 🚀 Quick Start  

### Prerequisites  
- Node.js v18+  
- Yarn or npm  
- MetaMask wallet  

### Installation  

1. **Clone the repo**  
   ```
   git clone https://github.com/insionCEO/EVM-Token-Launchpad.git
   cd EVM-Token-Launchpad
   ```
   
2. **Install dependencies** 
   ```
   # Frontend
   cd ui
   npm install

   # Smart Contracts
   cd contract
   npm install
   ```

3. **Set up environment variables** 

   Frontend: Create .env.local in /ui:
   ```
   NEXT_PUBLIC_CONTRACT_ADDRESS=
   NEXT_PUBLIC_RPC_URL=""
   NEXT_PUBLIC_MORALIS_API_KEY=
   ```

   Hardhat: Create .env in /contract:
   ```
   SEPOLIA_RPC_URL="https://site1.moralis-nodes.com/sepolia/......"
   PRIVATE_KEY=
   ```

4. **Run the project** 
   ```
   # Frontend (from /ui)
   npm run dev

   # Smart Contracts (from /contract)
   npx hardhat test
   npx hardhat node
   ```

## 📜 Smart Contracts
   - Deploy Contracts
   ```
   npx hardhat run scripts/deploy.ts --network sepolia
   ```
   - Verify on Etherscan
   ```
   npx hardhat verify --network sepolia DEPLOYED_CONTRACT_ADDRESS "Constructor Arg 1"
   ```

**Telegram**: [@insionCEO](https://t.me/insionCEO)
