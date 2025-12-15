# CKB Builder Notes – Week 2

##  Overview
This document contains my **Week 2 learning report** while continuing my journey with the **Nervos CKB blockchain**.  
After successfully setting up the development environment and understanding the core concepts in Week 1, this week focused mainly on **hands-on practice** using tutorials and basic exercises.

---

## 🗓️ Week 2 Learning Report

###  Practical Interaction with Nervos CKB
In this week, I started working on **basic exercises and official tutorials** provided in the Nervos CKB documentation. The main goal was to move from theory to **practical implementation**.

Through these exercises, I learned how to:
- Interact with the **CKB network** programmatically.
- Understand how data flows between local applications and the blockchain.
- Use tools provided by the CKB ecosystem effectively.

---

###  Working with Cells
I performed simple hands-on tasks related to **cells**, which are the core data structure of CKB.

Key learnings:
- How to **create cells**.
- How cells store capacity and data.
- How cells are **consumed and generated** during transactions.
- Understanding ownership and locking mechanisms at a basic level.

---

###  Scripts and Sample Execution
I experimented with **sample scripts** to understand how script execution works in real scenarios.

What I learned:
- How scripts are attached to transactions.
- How script validation ensures transaction correctness.
- How sample scripts help in understanding transaction verification logic.

---

###  RPC Connection Testing
I tested **RPC connections** to ensure proper communication between my local environment and the CKB network.

Activities performed:
- Connecting to local and test RPC endpoints.
- Sending basic RPC requests.
- Verifying responses from the network.

This helped me understand how decentralized applications communicate with the blockchain backend.

---

##  OffCKB Project Setup (Hands-on)

During this week, I also worked on setting up and running an **OffCKB project**.

Tasks completed:
- ✔ Created a new OffCKB project.
- ✔ Set up all required project dependencies.
- ✔ Started the local development server.
- ✔ Understood the basic **dApp project structure**.

Example commands used:
```bash
npm install
npm run dev
