# 🚀 SkillMint — Web3 NFT Achievement Platform

SkillMint is a modern Web3 credentialing and NFT achievement platform built using React, Vite, Tailwind CSS, Ethers.js, and Base Sepolia.

It allows users to create, customize, and mint blockchain-based achievement badges as NFTs through a premium gamified experience with MetaMask integration and real blockchain interactions.

---

# ✨ Features

* 🎨 Dynamic NFT Badge Customization
* ⛓️ Real Blockchain NFT Minting
* 🦊 MetaMask Wallet Integration
* 🌐 Base Sepolia Network Support
* 🏆 Gamified XP & Leaderboard System
* 👤 Public User Profiles
* 🌙 Dark / Light Theme Support
* ⚡ Smooth Framer Motion Animations
* 📱 Fully Responsive UI
* 🔒 Secure Wallet Session Isolation
* 🧠 Hybrid Web2 + Web3 Architecture

---

# 🛠️ Tech Stack

## Frontend

* React 19
* Vite
* TypeScript
* Tailwind CSS v4
* Framer Motion
* Radix UI
* Lucide Icons

## Routing & State

* TanStack Router

## Blockchain / Web3

* Ethers.js v6
* Solidity ERC721 Smart Contract
* Base Sepolia Testnet
* MetaMask

## Backend / Services (Configured)

* Clerk Authentication
* Supabase Database
* Pinata IPFS

---

# 🧩 Problem Statement

Traditional certificates and digital achievements are centralized and easily forgeable.

SkillMint solves this problem by leveraging blockchain technology to create immutable NFT-based achievement badges that can be permanently verified on-chain.

The platform also simplifies Web3 onboarding with a premium user experience and seamless wallet integration.

---

# 🏗️ Project Architecture

```text
Frontend (React + Vite)
        ↓
Wallet Layer (MetaMask + Ethers.js)
        ↓
Smart Contract (ERC721 on Base Sepolia)
        ↓
Metadata Storage (Base64 / IPFS)
        ↓
Optional Backend Services
(Clerk + Supabase + Pinata)
```

---

# 📂 Folder Structure

```text
src/
 ├── components/
 ├── routes/
 ├── lib/
 ├── styles/
 └── assets/

contracts/
 └── SkillMintBadge.sol
```

---

# ⚙️ Environment Variables

Create a `.env` file:

```env
VITE_CLERK_PUBLISHABLE_KEY=""
VITE_NFT_CONTRACT_ADDRESS=""
VITE_SUPABASE_URL=""
VITE_SUPABASE_ANON_KEY=""
VITE_PINATA_JWT=""
```

---

# 🔗 Smart Contract

Network: Base Sepolia

ERC721 Contract integrated with Ethers.js.

Current Contract Address:

```text
0x8F51CB0a8b7AeA5E20B21B9487701dAc57e2efb8
```

---

# 🚀 Installation & Setup

## Clone Repository

```bash
git clone https://github.com/Saniyapatil1501/skillmint-web3-platform.git
```

## Install Dependencies

```bash
npm install
```

## Start Development Server

```bash
npm run dev
```

## Production Build

```bash
npm run build
```

---

# 🦊 MetaMask Setup

1. Install MetaMask Extension
2. Switch Network to Base Sepolia
3. Import/Test Wallet
4. Add Test ETH from Faucet
5. Connect Wallet inside SkillMint

---

# 🌍 Deployment

Recommended Platform:

* Vercel

Deployment Steps:

1. Push code to GitHub
2. Import repository into Vercel
3. Add environment variables
4. Deploy

---

# 📸 Screenshots

> Add screenshots here before final submission.

* Home Page
* Dashboard
* NFT Studio
* Wallet Connection
* Mint Flow
* Leaderboard

---

# 🔮 Future Scope

* Gasless Relayer Integration (UGF)
* Real IPFS Metadata Hosting
* NFT Marketplace Support
* Multi-chain Expansion
* AI-based Badge Recommendations
* Admin Analytics Dashboard

---

# 👩‍💻 Author

Saniya Patil

---

# 📜 License

This project is licensed under the MIT License.

---

# 💡 Final Note

SkillMint was built as a modern startup-style Web3 platform focused on delivering a premium user experience while simplifying blockchain onboarding for non-crypto users.
