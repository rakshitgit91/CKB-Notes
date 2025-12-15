# CKB Builder Notes – Week 3

##  Overview
This document contains my **Week 3 learning report** as part of my ongoing exploration of the **Nervos CKB blockchain**.  
This week focused on **understanding the CKB Cell model in depth** and performing **real transactions** using the **CCC SDK**. I also learned how to **store and read data from Cells** on-chain.

---

##  Week 3 Learning Report

###  Viewing and Transferring a CKB Balance
I followed the official tutorial **“View and Transfer a CKB Balance”** to understand how balance management works in CKB.

Key concepts learned:
- How **capacity** represents ownership and storage.
- How **input cells** are consumed in a transaction.
- How **output cells** are created after a transfer.
- How transaction fees are handled using cell capacity.

Using the **CCC SDK**, I successfully executed a sample transfer and observed how cells change before and after the transaction.

Example flow:
```text
Input Cells  →  Transaction  →  Output Cells
