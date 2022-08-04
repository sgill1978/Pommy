# PommyATM Software

Developed by: Sukhkaran Gill.


 
Introduction: 
	I have been developing ATM software. This software allows the user to deposit and withdraw from multiple accounts. It requires a correct card and pin number to access the software. The ATM software includes other features including: withdrawal limit, and overdraft fees. All of these features make for a seamless user experience.

Instructions:
The ATM software will run on regular ATM machine hardware and will use C++ IDE to run the program because the software is written in C++.The software will run on most of the machine hardware of ATM machines. The architecture will include the ATM application that will have functionality for deposit, withdraw and view account balance The requirements section listed in this document lists the major requirements of this project.
Functions have been coded in C++ for deposit, withdrawals , balance inquiry and menu display in a header file named as Display1234.h .This BankDatabase1234.h header file has feature of exception (error) handling to validate user input for each of the functions of the ATM software.BankDatabase1234.h header files also, stores the user accounts number in linked list. Pin number, checking amount and savings amount are stored in an two dimensional array. For every transaction performed the checking and savings account are updated.          















The BankDatabase1234.h header file has functions to validate user account number and the ATM pin number. Bankdatabase1234.h header file also has a function to perform the ATM transaction. This function uses the functions  such as deposit, withdrawal, balance inquiry and display menu from Display1234.h header file. The functionality can be represented by Use cases as follows:
 













Finally in  the main source file (ATMApp1234.cpp)  an object of BankDatabase class is created and this object calls for the function to run the ATM functionality. Once the source code is executed by the IDE then the ATM software runs by presenting a menu for the ATM machine on the display to access the functionality of the software. The interaction can be represented by process flow diagram listed below;
 











Requirements:
●	Withdraw funds from an account function(Checking and Savings account).
○	The withdrawal feature was implemented in a function. The function gets the user input and checks if it is 200 dollars or below. If it is, the function takes the money out of the selected account.
●	Deposit funds to an account function (Checking and Savings account).
○	This feature prompts the user for the account they would like to deposit to. After the program gets the user's input and checks if it is proper input, it adds the amount to the account that the user selected.
●	Sign in and out functions
○	The sign in function asks the user for their account number and PIN. First it asks for the account number and checks whether the imputed number belongs to a recognized account. If it does, then the program prompts the user for the PIN number for the account. If the PIN matches the account number then the user will be able to access the account. 
●	Debit Card and Credit Account Information.
○	The card number is required to be entered correctly in order to access the account and make transactions. Each user will have a specific account number. 
●	PIN (Personal Identification Number).
○	The PIN number is specific to an account and is required to be entered correctly in order to access the account and program.
●	Overdraft fee
○	The overdraft fee subtracts from a user account if their account goes into the negatives. If the user withdrawals more from the account than is in the account it applies a fee. 



Summary: 
	In conclusion the ATM App is a program that allows users to perform basic ATM functions. The user will be able to sign in and make deposits and withdrawals. Features like overdraft fees are in place and will give a fee to users if their account goes negative. Other features such as withdrawal limits are in place to prevent users from withdrawing more than 200 dollars at a time. Checks are also in place to make sure that the user enters proper information that can be used by the program. 
