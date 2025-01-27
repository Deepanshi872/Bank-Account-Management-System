# Bank-Account-Management-System
This project is a Python-based simulation of a bank account management system. It allows users to create and manage bank accounts, perform transactions, and retrieve account details. The system demonstrates the application of fundamental Python concepts such as variables, data structures, functions, file handling, and modules.

# Features
1. Account Management
Create new bank accounts with the following attributes:
<br>      
Account holder's name
<br>
Auto-generated account number (11 digits)
<br>
Account type (e.g., savings or current)
<br>
Initial balance
<br>
Retrieve account details, including:
<br>
Account holder's name
<br>
Account number
<br>
Account type
<br>
Current balance
<br>
2. Transactions
Deposit: Add money to an account.
<br>
Withdrawal: Withdraw money, ensuring the withdrawal does not exceed the current balance.
<br>
Transfer: Transfer funds between two accounts with proper validation.
<br>
Transactions automatically update the account balances.
<br>
3. File Handling
<br>
Persistent storage of account details and transaction history using the pickle library.
<br>
Load account data at program startup and save updates on termination.
<br>
Append new transactions to existing records without overwriting previous data.
<br>
4. Reports
<br>
View transaction history for any account, displaying:
<br>
Date
<br>
Type of transaction (deposit, withdrawal, transfer)
<br>
Amount
<br>
Target account (if applicable)
<br>
Generate summary statistics for each account, including:
<br>
Total deposits
<br>
Total withdrawals
<br>
Average transaction amounts (using NumPy functions)
<BR>
5. User Interaction
<br>
An interactive menu for the following operations:
<br>
Open a new account
<br>
View account details
<br>
Perform transactions (deposit, withdraw, transfer)
<br>
View transaction history
<br>
Exit the program
<br>
Smooth navigation using conditional statements and loops.
<BR>
6. Error Handling

Input validation to ensure:

Positive amounts for deposits and withdrawals.

Adequate balance before withdrawal or transfer.

Prevent invalid operations like transferring funds between non-existent accounts.
<BR>
7. Bonus Features (Optional)
<br>
Login functionality for multiple users with username and password.
<br>
Advanced Python features like lambda functions for quick calculations.
<br>
Installation
<br>
Prerequisites
<br>
Python 3.8 or later
<br>
Required libraries:
<br>
NumPy
<br>
Pickle (built-in module)

