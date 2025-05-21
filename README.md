# DSA
Assignments and Projects
# Expense Tracking System

## Overview
This project is a **C++ Expense Tracking System** using **nested linked lists**. The program allows users to manage expenses for different accounts, where each account maintains a linked list of transactions.

It supports **CRUD operations** (Create, Read, Update, Delete), calculates total expenses, and securely searches for accounts and transactions.

## Features
- **Account Management**
  - Create a new account
  - Search for an existing account
  - View all accounts
  
- **Transaction Management**
  - Add transactions to an account
  - View transaction history
  - Calculate total expenses

- **Security & Validation**
  - Password-protected access for displaying all accounts
  - Multiple attempts for secure searching

## How to Use
 Compile and Run the Program
 
  Menu Options

1 → Create a new account

2 → Search an account using name and ID

3 → Add transactions to an existing account

4 → View the total number of accounts

5 → Calculate total expenses for an account

6 → Display all accounts (password required)

7 → Exit the program

Security

To view all accounts, enter the correct password (1234 by default).

Searching and adding transactions require correct account credentials.

Implementation Details
The Outer Linked List represents accounts.

Each account node contains an Inner Linked List for transactions.

Transactions include Purchase Amount and Description.

Doubly Linked List is used for easy navigation.


*****Example Output*****

===== Expense Management Menu =====
1. Create Account
2. Locate Account
3. Add Transaction to Account
4. View Total Accounts
5. View Total Expenses
6. Show All Accounts
7. Exit

Enter choice: 1
Enter Account Name: John Doe
Assigned Account ID: 1

Enter Amount: 500
Enter Details: Laptop Purchase
Press 'Y' to record another transaction: N

Transaction Added Successfully!
