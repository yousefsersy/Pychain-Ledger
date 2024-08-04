# PyChain Ledger: A Blockchain-Based Ledger System

![alt=""](Images/application-image.png)

---

## Project Background

The primary task of this project is to develop a blockchain-based ledger system with a user-friendly web interface. This system is designed to facilitate financial transactions between partner banks and ensure data integrity.

---
This Streamlit application simulates a blockchain ledger, enabling users to conduct financial transactions and verify data integrity.

## Key Features
- **Transaction Processing**: Users can enter a sender address, receiver address, and the amount of cryptocurrency to transfer. These transactions are recorded in the "PyChain Ledger."
- **Block Inspection**: The "Block Inspector" feature allows users to examine individual transactions by selecting them from a drop-down menu.
- **Chain Validation**: The "Validate Chain" function checks the integrity of the blockchain by comparing the hash of each block with the previous block's hash.

![alt text](<PyChain Ledger-1.png>)



## Recent Updates
1. **Record Class**: Introduced a new data class, `Record`, as a blueprint for financial transaction records stored in the ledger blocks.
2. **Block Class Modification**: Updated the existing `Block` data class to include `Record` data.
3. **Streamlit Interface Enhancements**: Added relevant user inputs to the application interface.
4. **PyChain Ledger Testing**: Tested the system by storing and verifying records.




