# CKB Builder Progress Report – Week 1

---

##  Overview
This repository contains my **weekly learning notes** while exploring the **Nervos CKB blockchain** as part of my learning journey.  
Week 1 focuses on understanding the **core concepts of CKB**, setting up the **development environment**, and getting started with **OffCKB** using official quick-start guides.

---

##  Week 1 Learning Report

###  Introduction to Nervos CKB
In the first week, I learned the **basic technical concepts and terminology** of the Nervos CKB blockchain. I focused on understanding how CKB differs from traditional blockchains and how its architecture is designed for scalability and security.

Key concepts covered:
- **Cells**: The fundamental data structure in CKB used to store state and assets.
- **Capacity**: Represents storage cost and ownership in the CKB network.
- **Tokens**: How assets are represented and managed using cells.

---

###  How Nervos Blockchain Works
I studied the working of the Nervos blockchain, including:
- **Consensus mechanism** and its importance in maintaining network security.
- How transactions consume and produce **cells**.
- The role of **CKBytes (CKB)** as both a token and storage resource.

---

###  Introduction to Scripts (Smart Contracts in CKB)
Scripts play a very important role in CKB.

What I learned:
- Scripts are used to **validate transactions**.
- They define **lock rules** (who can spend a cell).
- They define **type rules** (how a cell can be used).
- Every transaction must pass script validation to be considered valid.

This helped me understand how CKB provides flexibility while maintaining security.

---

###  Development Environment Setup
I followed the official **quick start guides** to set up my development environment.

Tasks completed:
- Installed required dependencies.
- Explored different **CKB networks** (Devnet, Testnet).
- Understood how **RPC endpoints** are used to communicate with the blockchain.
- Verified the setup by running basic commands.

Example commands used during setup:
```bash
node -v
npm -v
git --version

