\# 🌌 SkillMint



> A premium Web3 NFT achievement platform built on Base Sepolia with real blockchain minting, customizable badges, and gamified user experiences.



SkillMint is a decentralized Web3 application that allows users to mint proof-of-skill achievements as elegant, customizable NFTs on the Base Sepolia network.



The platform combines modern Web3 architecture with a premium startup-grade UI/UX experience featuring real blockchain minting, MetaMask integration, gamification systems, and dynamic NFT customization.



\---



\# ✨ Interactive Experience \& Features



\## 🎨 Dynamic NFT Customization Studio



Users can customize:



\* Skill Title

\* Recipient Name

\* Badge Level

\* Theme Colors

\* NFT Rarity



Supported themes:



\* Cyan

\* Emerald

\* Violet

\* Rose

\* Amber



Supported rarities:



\* Common

\* Rare

\* Epic

\* Legendary



\---



\## ⛓️ Real Blockchain NFT Minting



\* Real ERC-721 NFT minting on Base Sepolia

\* MetaMask wallet integration

\* Live transaction confirmations

\* BaseScan transaction links

\* On-chain ownership verification



\---



\## 🦊 MetaMask Wallet Integration



\* Secure wallet connection

\* Wallet isolation per authenticated user

\* Manual disconnect support

\* Auto network switching to Base Sepolia

\* Cross-session wallet protection



\---



\## 🏆 Gamification \& Leaderboards



\* XP-based progression system

\* NFT rarity-based scoring

\* Public user achievement profiles

\* Competitive leaderboard architecture



\---



\## 🌙 Modern Premium UI/UX



\* Glassmorphism aesthetics

\* 3D NFT card tilt effects

\* Framer Motion animations

\* Responsive layouts

\* Neon-inspired modern design system

\* Dark/Light theme support



\---



\# 🛠️ Tech Stack



\## Frontend



\* React 19

\* Vite 7

\* TypeScript

\* Tailwind CSS v4

\* Framer Motion

\* Radix UI

\* Lucide React

\* Sonner



\---



\## Routing \& State Management



\* TanStack Router

\* TanStack Start



\---



\## Blockchain \& Web3



\* Ethers.js v6

\* Solidity

\* ERC-721 Smart Contract

\* Base Sepolia Testnet

\* MetaMask Integration



\---



\## Backend \& Services



\* Supabase

\* Clerk Authentication

\* Pinata IPFS

\* Cloudflare Workers



\---



\# 🧩 Problem Statement



Traditional certificates and achievement systems are centralized, forgeable, and difficult to verify globally.



SkillMint solves this problem using blockchain technology by enabling immutable NFT-based proof-of-skill achievements that can be permanently verified on-chain.



The platform also simplifies Web3 onboarding through a beginner-friendly experience with premium UI/UX and seamless wallet integration.



\---



\# 🏗️ Project Architecture



```text id="ar6n1y"

Frontend (React + Vite + Tailwind)

&#x20;           ↓

Wallet Layer (MetaMask + Ethers.js)

&#x20;           ↓

Smart Contract (ERC721 on Base Sepolia)

&#x20;           ↓

Metadata Layer (Base64 / IPFS)

&#x20;           ↓

Backend Services

(Supabase + Clerk + UGF Architecture)

```



\---



\# 🛡️ Smart Contract



The core smart contract is located in:



```text id="lt0bsa"

contracts/SkillMintBadge.sol

```



\### Contract Details



\* Standard: ERC721URIStorage

\* Solidity Version: ^0.8.20

\* Network: Base Sepolia



\### Key Function



```solidity id="qqv4jh"

mintBadge(address to, string memory tokenURI)

```



This function allows minting customizable NFT achievement badges with metadata support.



\---



\# 📂 Folder Structure



```text id="v4r4t4"

├── contracts/

│   └── SkillMintBadge.sol



├── src/

│   ├── components/

│   │   ├── layout/

│   │   ├── skillmint/

│   │   └── ui/

│   │

│   ├── hooks/

│   ├── lib/

│   │   ├── blockchain.ts

│   │   ├── auth.tsx

│   │   └── db.ts

│   │

│   ├── routes/

│   │   ├── index.tsx

│   │   ├── dashboard.tsx

│   │   ├── explore.tsx

│   │   ├── leaderboard.tsx

│   │   ├── studio.tsx

│   │   └── u.$username.tsx

│   │

│   ├── main.tsx

│   ├── server.ts

│   └── styles.css

│

├── .env

├── package.json

├── wrangler.jsonc

└── README.md

```



\---



\# ⚙️ Environment Variables



Create a `.env` file in the root directory.



```env id="lmxec8"

\# Clerk Authentication

VITE\_CLERK\_PUBLISHABLE\_KEY=""



\# Smart Contract Address

VITE\_NFT\_CONTRACT\_ADDRESS="0x8F51CB0a8b7AeA5E20B21B9487701dAc57e2efb8"



\# Supabase

VITE\_SUPABASE\_URL=""

VITE\_SUPABASE\_ANON\_KEY=""



\# Pinata IPFS

VITE\_PINATA\_JWT=""

```



\---



\# 🚀 Getting Started



\## 1. Clone Repository



```bash id="2j81vg"

git clone https://github.com/Saniyapatil1501/skillmint-web3-platform.git

```



\---



\## 2. Move Into Project Folder



```bash id="z0pw4g"

cd skillmint-web3-platform

```



\---



\## 3. Install Dependencies



```bash id="8j94jt"

npm install

```



\---



\## 4. Run Development Server



```bash id="ly7jma"

npm run dev

```



Open:



```text id="4nt1mt"

http://localhost:8080

```



\---



\## 5. Production Build



```bash id="qim5di"

npm run build

```



\---



\# 🦊 MetaMask Setup



1\. Install MetaMask Extension

2\. Add Base Sepolia Network

3\. Get Base Sepolia Test ETH

4\. Connect Wallet inside SkillMint

5\. Mint NFT badges on-chain



\---



\# 🌍 Deployment



\## Recommended Platform



\* Vercel



\## Deployment Steps



1\. Push repository to GitHub

2\. Import repository into Vercel

3\. Add environment variables

4\. Deploy



\---



\# ⚡ Smart Contract Deployment



The project uses a real ERC-721 smart contract deployed on Base Sepolia.



\### Deployment Options



\* Remix IDE

\* Hardhat

\* Foundry



\### Steps



1\. Compile Solidity contract

2\. Deploy to Base Sepolia

3\. Copy deployed contract address

4\. Update `.env`



\---



\# 📸 Screenshots



Add screenshots here before submission:



\* Landing Page

\* Dashboard

\* NFT Studio

\* Wallet Connection

\* NFT Minting Flow

\* Leaderboard



\---



\# 🔮 Future Scope



\* Fully Gasless UGF Relayer Backend

\* Real IPFS Metadata Hosting

\* NFT Marketplace Integration

\* AI-based Badge Recommendations

\* Multi-chain Support

\* Admin Analytics Dashboard

\* DAO Governance Features



\---



\# 📜 License



Distributed under the MIT License.



\---



\# 👩‍💻 Author



Saniya Patil



\---



\# 💡 Final Note



SkillMint was built as a premium startup-style Web3 platform focused on simplifying blockchain onboarding for non-crypto users while maintaining a modern and engaging user experience.



The platform demonstrates real-world integration of Web3 technologies, blockchain interactions, NFT architecture, gamification systems, and modern frontend engineering practices.



