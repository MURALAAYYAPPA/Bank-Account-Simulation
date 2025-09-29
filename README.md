
# Bank Account Simulation – Java

NAME : MURALA AYYAPPA 

## Introduction

This project is a Bank Account Simulation System implemented in Java. It demonstrates how to use Object-Oriented Programming (OOP) concepts such as classes, objects, encapsulation, and method overriding to model real-world banking operations.

The project provides a simple console-based interface where users can create an account, deposit money, withdraw money, check their balance, and view their transaction history.

---

## Objective

* To design a class-based Java program that performs fundamental banking operations.
* To simulate real-world scenarios such as deposits, withdrawals, and account management.
* To strengthen understanding of Java OOP principles and how they are applied in practical applications.

---

## Features

1. Account Creation – A user can create a new account with an initial deposit.
2. Deposit Money – Users can deposit funds into their account, and the balance updates accordingly.
3. Withdraw Money – Users can withdraw money if sufficient funds exist.
4. Balance Inquiry – Users can check their current account balance anytime.
5. Transaction History – All deposits and withdrawals are stored in a log for reference.
6. Error Handling – Prevents invalid deposits (negative or zero amounts) and withdrawals beyond the available balance.

---

## Key Concepts Used

* Classes and Objects – To model accounts and their operations.
* Encapsulation – Account balance and transaction history are private, accessed only via methods.
* Constructors – Used to initialize account details when a new account is created.
* ArrayList – Stores transaction history dynamically.
* Control Structures – Switch case and loops used to provide a menu-driven program.

---

## How It Works

1. The program starts by asking the user to enter their name and initial deposit.
2. A new Account object is created with these details.
3. The user is presented with a menu:

   * Deposit
   * Withdraw
   * Check Balance
   * View Transactions
   * Exit
4. Each choice performs the respective operation, updating the account state and recording history.
5. The user can continue until they choose to exit.

---

## Project Structure

BankSimulation.java   → Contains the main program with menu
Account.java          → Defines the Account class with fields and methods
README.md             → Documentation for the project

---

## Steps to Run the Program

1. Clone the repository or download the source code.
   git clone [https://github.com/MURALAAYYAPPA/BankAccountSimulation-Java.git]
   cd BankAccountSimulation-Java

2. Compile the Java program:
   javac BankSimulation.java

3. Run the program:
   java BankSimulation

---

## Example Flow

Enter account holder name: Alice
Enter initial deposit: 5000

--- Bank Menu ---

1. Deposit
2. Withdraw
3. Check Balance
4. Transaction History
5. Exit
   Enter choice: 1
   Enter deposit amount: 2000
   Deposited: 2000

Enter choice: 3
Current Balance: 7000

---

## Learning Outcomes

* Understand how OOP concepts work in real-world problem solving.
* Gain hands-on practice with Java classes, methods, and encapsulation.
* Learn how to build interactive console applications.
* Develop skills in maintaining transaction records and simulating user actions.

---

## Future Enhancements

* Add support for multiple accounts using HashMap.
* Implement account authentication (username and password).
* Store transaction history in an external file or database.
* Add an interest calculation feature for savings accounts.
* Provide a GUI version using JavaFX or Swing.

OUTPUT : 

