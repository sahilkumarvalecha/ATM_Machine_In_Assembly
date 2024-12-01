# ATM Machine in Assembly Language  

## **Project Overview**  
This project implements a simple ATM Machine simulator using Assembly language. It showcases fundamental banking operations including:  
- **Balance Inquiry**  
- **Cash Withdrawal**  
- **PIN Verification**

The goal of this project is to explore low-level programming while simulating a real-world banking application.  

---

## **Features**  
- PIN authentication to access the system.  
- View the current balance.  
- Withdraw cash with balance validation.  
- Exit the system gracefully.  

---

## **Getting Started**  
### **Prerequisites**  
- **Assembler**: Ensure you have a compatible assembler (e.g., Emu8086) installed on your system.  
- **Operating System**: The project is tested on DOS/Windows environments.  

### **Installation**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/sahilkumarvalecha/atm-machine.git
   cd atm-machine
   ```
2. Assemble the source code:  
   ```bash
   nasm -f bin atm.asm -o atm.bin
   ```
3. Run the program using an emulator (e.g., Emu8086):  
   ```bash
   dosbox atm.bin
   ```

---

## **Usage**  
1. Compile and run the program in an assembly-compatible environment.  
2. Enter the correct PIN to proceed.  
3. Select from the available operations:  
   - View Balance  
   - Withdraw Cash  
   - Exit  

Follow on-screen instructions to perform the desired operation.

---

## **Project Contributors**  
- **Sahil Kumar Valecha**  
- **Saleena Ahuja**
- **Paras Parveen**  
