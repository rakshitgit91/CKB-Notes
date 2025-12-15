# CKB Builder Notes – Week 4

##  Overview
This document contains my **Week 4 learning report** as part of my ongoing hands-on exploration of the **Nervos CKB blockchain**.  
This week focused on **token issuance** using the **xUDT standard** and **custom script development** by building a simple lock script. I also continued working with the **OffCKB + CCC SDK development environment** to deploy and observe real on-chain behavior.

---

##  Week 4 Learning Report

###  Creating a Fungible Token (xUDT)
I worked through the tutorial **“Create a Fungible Token (xUDT)”** to understand how custom tokens are issued on Nervos CKB.

Key learnings:
- xUDT is implemented using **CKB’s Cell Model** rather than account-based balances.
- A special **cell with a type script** defines the token logic.
- The **data field of the cell** stores the token amount.
- The **issuer’s lock script hash** is used as the unique **token ID**, ensuring uniqueness and ownership.

Steps performed:
- Created an xUDT type script cell.
- Initialized the token supply.
- Verified token balance by inspecting output cells on DevNet.

This exercise helped me understand how CKB enables flexible asset issuance without hard-coded token logic.

---

###  Understanding Token Representation in CKB
Through this exercise, I learned:
- Tokens are represented as **cells**, not accounts.
- Transfers involve consuming input cells and creating new output cells.
- Validation is enforced by **type scripts** rather than centralized logic.

This reinforced my understanding of how CKB provides a powerful and extensible asset model.

---

###  Building a Simple Lock Script
I followed the **“Build a Simple Lock”** tutorial to learn how custom lock scripts work.

Project overview:
- Implemented a **toy lock script** based on a **hash preimage**.
- Funds are locked until the correct preimage is provided.
- The script verifies the hash before allowing the cell to be unlocked.

Implementation details:
- Developed the **backend lock script** logic.
- Created a **basic frontend interface**.
- Users unlock tokens by submitting the correct preimage value.

This helped me understand how **lock scripts control ownership and spending conditions** in CKB.

---

###  Development Environment & Deployment
To support the above exercises, I:
- Installed and configured the **OffCKB development environment**.
- Used the **CCC SDK** for interaction with the CKB network.
- Cloned and explored sample projects.
- Deployed and ran example code on **DevNet**.

Example workflow:
```bash
git clone <sample-project>
npm install
npm run dev
