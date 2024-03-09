# Banking System Simulation

Created by Ajith_vijayanD25

Title: Kochi Express Bank - Banking System Simulation

Synopsis:
Kochi Express Bank - Banking System Simulation is a Python-based project that simulates the operations of a fictional bank. The project provides users with a menu-driven interface to perform various banking operations such as account creation, login, deposit, withdrawal, and mini statement viewing. The simulation aims to replicate the functionalities of a real banking system while providing a user-friendly experience.

Functionalities for Users:

1)Create New Account: As a new customer, you can create a new bank account by providing your name, mobile number, and PIN. Upon successful account creation, you 
                       receive an initial deposit of 100 rupees.
2)Log In: Existing customers can log in to their accounts by entering their mobile number and PIN. Once logged in, they can perform various banking operations.
3)Deposit Money: Customers can deposit money into their accounts by specifying the amount they want to deposit.
4)Withdraw Money: Customers can withdraw money from their accounts by specifying the amount they want to withdraw, provided they have sufficient funds.
5)Transfer Money: Customers can transfer money from their account to another account by entering the recipient's mobile number and the amount to be transferred.
6)Mini Statement: Customers can view a mini statement of their account, which includes details such as account holder name, mobile number, account number, and current 
                   balance.

Concepts Used in the Program:

1)Object-Oriented Programming (OOP): The program utilizes OOP principles by defining a class Bank to encapsulate the bank's functionalities. Each method within the 
                                     class represents a specific operation that can be performed on a bank account.
2)Class and Instance Variables: Static variables like bankname, branch, accountnum, and accounts are declared at the class level and are shared among all instances of 
                                 the class. Instance variables like username, mobile, pin, and balance are unique to each instance of the class.
3)Constructor Method (__init__): The constructor method is called automatically when a new instance of the Bank class is created. It initializes the state of the 
                                 object by setting its attributes.
4)Methods: Methods such as deposit, withdraw, mini_statement, login, and transfer define the behavior of the Bank class. They encapsulate specific functionalities of 
           the banking system.
5)Input Validation: The program validates user inputs such as mobile number and PIN to ensure they meet certain criteria (e.g., length and format).
6)Looping Constructs: The program uses a while loop to continuously prompt the user for input until they choose to exit the program.
7)User Interface: The program provides a menu-driven interface for users to interact with the banking system. Users can select options from the menu to perform various 
                   banking operations.
8)Output Formatting: ANSI escape codes are used to format output messages, providing a visually appealing interface for users.


