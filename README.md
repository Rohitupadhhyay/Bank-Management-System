🏦 Bank Management System in C

A menu-driven Bank Management System built in C language using file handling. The program allows users to create and manage simple bank accounts with persistent storage.


📋 Features

Create a new account with name and account number

Deposit money into an account

Withdraw money with balance validation

Check account balance

Stores account records in a binary file (account.dat) for persistence

Handles edge cases such as invalid account numbers and insufficient balance


⚙️ Technologies Used

C Programming

File Handling (fopen, fwrite, fread, fseek)

Structures for account data management

Binary file storage for efficient record keeping


🚀 How to Run

Clone the repository

git clone https://github.com/rohitupadhhyay/Bank-Management-System

cd ./Bank-Management-System


Compile the program

gcc bank.c -o bank


Run the system

./bank


📖 Menu Options

Create Account – Register a new account (initial balance = 0)

Deposit Money – Add money to an existing account

Withdraw Money – Withdraw money if balance is sufficient

Check Balance – View account balance by account number

Exit – Close the program


📝 Example Output
*** Bank Management System ***
1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. Exit
Enter your choice:
