
# A.I NFT Minting Application  
An application where users can create generative artworks by typing a detailed description. It uses stable diffusion technique to create AI-generated artworks. We can mint those artworks as NFT's and store them on IPFS. 


## ⚙️ Working

* Writing smartcontracts in solidity programming language, using Ethereum Blockchain. 
* Using stable diffusion model for A.I Image generation, hugging Face API Provides that. 
* Upload the images to IPFS on nft.storage (free storage for NFT's), post images to IPFS, it will give you hash values, and we can store those on On-chain. 
* Using Hardhat development framework, for creating smart contracts, deploying scripts, etc. 
* using ether.js where the JavaScript applications can talk directly to the blockchain from client-side application. 
* using HUGGING_FACE_API and NFT_STORAGE_API key. 
* Used Oppenzeppelin framework to build secure smart contracts, using ownable.sol contract from openzeppelin which helps you to manage the ownership of the contract. ownable.sol let's you transfer and renounce ownership.


## Article 

Checkout my Article on **Hashnode** 

[![portfolio](https://img.shields.io/badge/how_crypto_wallets_work-000?style=for-the-badge&logo=hashnode&logoColor=lightgreen)](https://student-communities.hashnode.dev/how-crypto-wallets-work)

## 🚀 About Me
A pre-final year student underGrad. My major is Computer Science and I do Problem Solving(Data Structures and Algorithms) for fun. I currently practise at Leetcode and participate in Leetcode contests using java. I have solved over 300 problems on LeetCode. I am well versed with Computer Science fundamentals like OOPS, Operating Systems, Database Management Systems, Computer Networks and also have keen interest in High Level System Design. I have built few projects on Web Development using MongoDB, Express, ReactJS and Node.js, and currently exploring Web3 & Blockchain development and building DApps. I am interested and open to interview as an intern in Software Engineering domain. 

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](http://localhost:3001/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/utkarsh-hadgekar-9a0b411a5/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ft_utkarsh)
[![NFT Collection](https://img.shields.io/badge/NFT_Collection-000?style=for-the-badge&logo=opensea&logoColor=white)](https://testnets.opensea.io/assets/goerli/0x3B564f2Ed3D6A57825244AdbEc371Be985Be772F/1)

## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)



## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)
- [NFT.Storage](https://nft.storage/) (Connection to IPFS)
- [Hugging Face](https://huggingface.co/) (AI Models)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Setup .env file:
Before running any scripts, you'll want to create a .env file with the following values (see .env.example):

- **REACT_APP_HUGGING_FACE_API_KEY=""**
- **REACT_APP_NFT_STORAGE_API_KEY=""**

You'll need to create an account on [Hugging Face](https://huggingface.co/), visit your profile settings, and create a read access token. 

You'll also need to create an account on [NFT.Storage](https://nft.storage/), and create a new API key.

### 4. Run tests
`$ npx hardhat test`

### 5. Start Hardhat node
`$ npx hardhat node`

### 6. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`
