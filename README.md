
# Blockchain Message Board
# 區塊鏈留言板

**Author:** Liu Zijing  
**Major:** Department of Physics, National Kaohsiung Normal University  

**作者：** 劉子敬  
**系所：** 國立高雄師範大學 物理學系  

---

# 🚀 Live Demo
# 🚀 即時展示

### 🌐 DApp Interface

Try the live decentralized application:

https://YOUR_GITHUB_USERNAME.github.io/blockchain-messageboard

(You can also open `index.html` directly in this repository.)

### 🔗 Smart Contract (Sepolia)

Contract Address:

`0xd7c8A9366Bd849990be3Fb42f49B4ff3A0D49518`

View on Etherscan:

https://sepolia.etherscan.io/address/0xd7c8A9366Bd849990be3Fb42f49B4ff3A0D49518

### 📄 Technical Report

Detailed explanation of the project:

`technical_report.pdf`

---

# Project Overview
# 專題概述

This project implements a **decentralized message board (DApp)** using an Ethereum smart contract.

Users can:

- Write a message to the blockchain
- Read the current message stored on-chain

This demonstrates the basic workflow of a blockchain application:

Smart Contract → Deployment → Wallet Interaction → Web Interface

本專題實作一個 **去中心化留言板 (Decentralized Application, DApp)**。

使用者可以：

- 將訊息寫入區塊鏈
- 從區塊鏈讀取訊息

本專題展示區塊鏈應用的基本流程：

智能合約 → 部署 → 錢包互動 → 網頁介面

---

# System Architecture
# 系統架構

User (Browser)  
│  
│ MetaMask Wallet  
│  
Frontend (HTML + JavaScript)  
│  
│ Web3 interaction  
│  
Ethereum Sepolia Testnet  
│  
Smart Contract (Solidity)

---

# Technologies Used
# 使用技術

### Blockchain
- Ethereum
- Sepolia Testnet

### Smart Contract
- Solidity 0.8.x
- Remix IDE

### Wallet
- MetaMask

### Frontend
- HTML
- JavaScript
- Ethers.js

---

# Smart Contract

### Contract File

`MessageBoard.sol`

### Functions

#### setMessage

`setMessage(string memory _msg)`

Write a message to the blockchain.  
將留言寫入區塊鏈。

#### getMessage

`getMessage()`

Return the current message stored on-chain.  
讀取目前區塊鏈上的留言。

---

# Contract Address
# 合約地址

Sepolia Testnet:

`0xd7c8A9366Bd849990be3Fb42f49B4ff3A0D49518`

View on Etherscan:

https://sepolia.etherscan.io/address/0xd7c8A9366Bd849990be3Fb42f49B4ff3A0D49518

---

# How to Run the Project
# 專題重現步驟

1. Open Remix IDE  
2. Create `MessageBoard.sol`  
3. Compile with Solidity 0.8.x  
4. Connect MetaMask  
5. Deploy to Sepolia testnet  
6. Call `setMessage("Hello NTUT")`  
7. Read the message using `getMessage()`

---

# Screenshots
# 系統畫面

### Smart Contract Deployment
![deploy](images/deploy.png)

### Write Message
![setMessage](images/setMessage.png)

### Transaction Queue
![transaction](images/transcation.png)

### Read Message
![result](images/result.png)

---

# Learning Outcomes
# 學習成果

Through this project we learned:

- Solidity smart contract development
- Ethereum testnet deployment
- MetaMask wallet interaction
- Web3 frontend integration

透過本專題，我們學習到：

- Solidity 智能合約撰寫
- Ethereum 測試網部署
- MetaMask 錢包互動
- Web3 前端整合

---

# Future Improvements
# 未來改進

Possible extensions:

- Multi-user message board
- Message history storage
- Full DApp frontend UI
- Deployment to Ethereum mainnet
