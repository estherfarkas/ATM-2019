# ATM-2019
This is an ATM program I created in Java in CISC 3115- Advanced Java Programming
The program reads multiple input files- one to fill the initial accounts, and the second to mimic user commands.
The information is stored in ArrayLists of Account objects, within a Bank class. This is to protect client information.
Each nested class is private and requires gettors and settors to access. 
The program is menu driven, and uses switch statements so the user can decide which operation they would like it to perform
Each switch statement directs the program to a different method within the main program.
The main program deals exclusively with input and output; all changes are made within the Bank and Account classes
Account objects contain all the client information as well as an ArrayList of TransactionReceipts. 
After every operation, the transaction receipt is printed to an output file. 
Exceptions are handled within the program via custom exception handlers. 
