Java Bank Account

A simple Java banking application that demonstrates the use of interfaces, custom exceptions, and basic bank account operations.

Features
Create a savings account
Deposit money
Withdraw money
Check account balance
Validate invalid amounts
Handle insufficient balance
Handle invalid operations
Concepts Used
Java Interface
Classes and Objects
Exception Handling
Custom Exceptions
Method Overriding
Scanner for user input
Conditional Statements
How It Works

The program defines a BankAccount interface with methods for deposit, withdrawal, and balance checking. The SavingsAccount class implements this interface.

Custom exceptions are used to handle invalid amounts and insufficient balance conditions. The user enters the account details and selects an operation such as Deposit, Withdraw, or Balance.

The program then performs the selected operation and displays the result.

Operations
Deposit
Withdraw
Balance
Exception Handling

The program uses two custom exceptions:

InvalidInputException – handles invalid or non-positive amounts.
InsufficientBalanceException – handles withdrawal amounts greater than the available balance.
User Input

The program accepts:

Account Holder Name
Account Number
Initial Balance
Operation type
Deposit amount or withdrawal amount when required
Sample Menu
Account Holder Name:
Account Number:
Initial Balance:
Operation (Deposit / Withdraw / Balance):
Deposit
Deposit Amount:
Successfully deposited: <amount>
Updated Balance: <balance>
Withdraw
Withdraw Amount:
Successfully withdrew: <amount>
Updated Balance: <balance>
Balance
Current Balance: <balance>
How to Run
Make sure Java is installed on your computer.
Open a terminal in the project folder.
Make sure the source file is named Main.java.
Compile the program:
javac Main.java
Run the program:
java Main
Enter the required account details and select the operation.
File Structure
Java-Main/
└── Main.java
Author

Sri Aishwarya D
