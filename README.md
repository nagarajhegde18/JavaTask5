# 🏦 Bank Account Simulation (Java OOP)

## 📌 Objective
A simple Java console-based bank account simulation that demonstrates **Object-Oriented Programming** concepts like **classes, methods, encapsulation**, and **transaction history**.

## 🛠 Tools Used
- Java (JDK 17+ recommended)
- VS Code (or any Java IDE)
- Terminal/Command Prompt

## 📂 Project Structure
- BankAccountSimulation.java


## 🚀 Features
- Create a bank account with an initial balance.
- **Deposit** money into the account.
- **Withdraw** money (with balance check).
- View **current balance**.
- Maintain and display **transaction history**.
- Menu-driven interface for smooth user interaction.

## 📜 Class Overview
### **Account**
- `deposit(double amount)` → Adds money to the account.
- `withdraw(double amount)` → Withdraws money if sufficient balance exists.
- `getBalance()` → Returns current account balance.
- `showTransactionHistory()` → Displays all account transactions.

### **BankAccountSimulation (Main Class)**
- Handles user input.
- Displays a **menu** for banking operations.
- Uses `Account` object for transactions.

## 🖥 How to Run

### **1. Compile the Program**
```bash
Run This Program
java BankAccountSimulation

Sample Output:
Enter account holder name: John
Enter initial deposit: ₹5000

===== BANK MENU =====
1. Deposit
2. Withdraw
3. Check Balance
4. Transaction History
5. Exit
Enter choice: 1
Enter deposit amount: ₹2000
✅ Deposit successful!

===== BANK MENU =====
1. Deposit
2. Withdraw
3. Check Balance
4. Transaction History
5. Exit
Enter choice: 3
💰 Current Balance: ₹7000

javac BankAccountSimulation.java

