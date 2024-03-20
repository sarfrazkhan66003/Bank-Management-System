# Bank-Management-System
Bank management system program in c++ using opps concept.
#This C++ program implements a simple bank management system using object-oriented programming (OOP) concepts along with file handling.

This C++ program implements a simple bank management system using object-oriented programming (OOP) concepts along with file handling. Here's a breakdown of its functionality and structure:

Classes:

There's a single class named Bank. This class contains public member variables to represent various attributes of a bank account such as name, address, phone, email, account number, account type, and balance.
Functions:

create_account(): This function allows users to create a new bank account by taking input for various account attributes and storing them in a file named "Bank.txt".
display_account(): It reads data from the "Bank.txt" file and displays the details of all existing bank accounts.
modify_account(): Allows modification of account details such as name, address, phone, email, account number, account type, and balance for a given account name. It does this by reading data from the file, modifying the required account, and then updating the file.
search_by_name(): Searches for a bank account by name and displays its details if found.
display_all(): Displays details of all bank accounts stored in the file.
delete_account(): Deletes a bank account by name by creating a temporary file, copying all accounts except the one to be deleted to the temporary file, and then renaming it to replace the original file.
Main Function:

The main() function provides a menu-driven interface to interact with the bank management system. It repeatedly prompts the user to choose from various options like creating, displaying, modifying, searching, displaying all, or deleting an account until the user chooses to exit.
File Handling:

Input and output operations are performed on a file named "Bank.txt" using file streams (ifstream for reading and ofstream for writing). This file acts as a database to store account details persistently.
Error Handling:

Basic error handling is implemented to handle invalid input choices.
