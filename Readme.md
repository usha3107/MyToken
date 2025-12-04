# MyToken (MTK)

## 📌 Overview
MyToken (MTK) is a simple ERC-20 compatible token built on the Ethereum blockchain using Solidity.  
It is created purely for learning and educational purposes to understand how ERC-20 tokens work.

This token follows the standard ERC-20 implementation, including transfers, approvals, allowances, and events.

---

## 📊 Token Details
| Property       | Value                     |
| -------------- | ------------------------- |
| *Name*         | MyToken                   |
| *Symbol*       | MTK                       |
| *Decimals*     | 18                        |
| *Total Supply* | 1,000,000 MTK (1 million) |

All tokens are minted to the deployer address upon contract deployment.

---

## ✨ Features
- ✔ Fully ERC-20 compatible  
- ✔ Transfer tokens between addresses  
- ✔ Approve other accounts to spend tokens  
- ✔ transferFrom functionality  
- ✔ Emits Transfer and Approval events  
- ✔ Tracks balances and allowances  
- ✔ Easy to deploy using RemixIDE  

---

## 🚀 How to Deploy (Using Remix IDE)

1. Open **https://remix.ethereum.org/**
2. Create a new file called *MyToken.sol*
3. Paste your token contract code
4. Go to *Solidity Compiler* → select version *0.8.x*
5. Click *Compile MyToken.sol*
6. Go to *Deploy & Run Transactions*
7. Select environment: *JavaScript VM*
8. In constructor field, enter total supply (for 1,000,000 tokens with 18 decimals):