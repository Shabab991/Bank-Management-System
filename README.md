# Bank-Management-System

The banking sector occupies a large part of the tertiary sector because which data maintained is too much by a single application. Using C language we can create an application that can manage the data of the Bank,  we use basic knowledge of C like string, array, structures, etc.

The functionality of the Bank Management System Application is mentioned below:

(i) Transfer Money to the Account
(ii) Creation of Account
(iii) Check Amount
(iv) Login Functionality


This article focuses on how to create a bank account system using C language and File handling in C.
Approach:
Let’s discuss the approach in detail, covering all the functions and their explanation in detail-

1. Create a Menu in the main function and create different functions for the Menu, which will be called using switch case statements. There are four different functions-
(i) account()- This function is used to create a new account.
(ii) transfermoney()- This function is used to transfer money to the account
(iii) checkbalance()- This function is used to check the balance in the account.
(iv) login()- This function is used to login into the account.

2. First, create an account of our user by calling the account() function after the creation of an account, store all the data into a file using file handling functions.

3. Then the user is able to transfer the amount to other users, for that transfermoney() function is called, and for checking the current balance in the account call checkbalance() function.

Concepts of file handling will be used to store the data of the users, and then read all data from that particular file, store structures in a file because they are easy to write and read.
Implementation:
Let’s look at the C implementation of each of the modules of the program and finally consolidate all the modules together and create a full working program.


