# Banking Management System

A simple console-based Banking Management System developed in C++ using Object-Oriented Programming concepts and File Handling.  
This project allows users to create bank accounts, login securely, deposit money, withdraw money, check balance, and view transaction history.

## Features

- Create New Bank Account
- Secure Login System
- Deposit Money
- Withdraw Money
- Check Account Balance
- View Account Details
- View Transaction History
- File Handling for Data Storage
- Colored Console Output

## Technologies Used

- C++
- Object-Oriented Programming (OOP)
- File Handling
- STL Vector
- Console Application

## Project Structure

- Each account is stored in a separate `.txt` file
- Transaction history is also saved in the same file
- Bank account numbers are generated automatically

## Functionalities

### 1. Create Account
Users can create a new bank account by providing:
- Full Name
- Email
- Phone Number
- Aadhaar Number
- Password

### 2. Login
Users can login using:
- Account Number
- Password

### 3. Deposit Money
Users can deposit money into their account.

### 4. Withdraw Money
Users can withdraw money if sufficient balance is available.

### 5. Check Balance
Displays current account balance.

### 6. Account Details
Displays all account information.

### 7. Transaction History
Shows all deposits and withdrawals.

## File Handling

The system stores:
- Account Details
- Balance
- Transaction History

inside text files using:
```cpp
ofstream
ifstream
