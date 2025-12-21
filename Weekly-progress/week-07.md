# CKB Builder Notes – Week 7

---

##  Weekly Report Summary -- Intro to Script (Class 1 & 2)

This week, I learned the fundamentals of **CKB on-chain scripts** and their role in transaction validation.

- **Class 1:**  
 Learned about the CKB validation model and the concept of scripts executed in the CKB-VM.
 Understood the difference between **Lock Scripts** (ownership control) and **Type Scripts** (cell usage rules).  
 Studied the structure of a script: `code_hash`, `hash_type`, and `args`.

- **Class 2:**  
 Learned how to write and deploy script code on CKB.  
 Understood that scripts are **RISC-V executables** executed by the CKB virtual machine.  
 Explored a simple C-based script example and the compilation process.

---

##  Sample Script Code (C)

Below is a simple example of a CKB script written in C.  
This script always returns success (`0`), meaning the transaction is valid.

```c
#include <stdint.h>

// Entry point for CKB VM
int main() {
    // Return 0 means script validation success
    return 0;
}
