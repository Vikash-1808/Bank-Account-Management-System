# Bank-Account-Management-System
**Overview**
The Bank Account Management System is a Java-based desktop application designed to manage customer bank accounts efficiently. The system allows users to create accounts, perform transactions (deposit, withdrawal), view balances, and maintain transaction history. The backend uses an SQL database for data storage and retrieval.

**Features**
User Authentication: User registration and secure login.
Account Management: Create, update, and delete bank accounts.
Transaction Management: Perform deposits, withdrawals, and fund transfers between accounts.
Balance Inquiry: View the current balance for each account.
Transaction History: View detailed transaction logs.
Admin Interface: Manage users and accounts as an admin.
Data Persistence: All data is stored in an SQL database for security and efficiency.

**Technologies Used**
Programming Language: Java (JDK 8 or above)
Database: MySQL (or any other SQL-based database)
GUI Framework: Swing (for desktop application interface)
Database Connectivity: JDBC (Java Database Connectivity)

**Prerequisites**
Java JDK (version 8 or above)
MySQL or any other SQL-based database
Maven or Gradle (depending on your build tool)
MySQL Connector (JDBC driver)

**Database Schema**
The following are the key tables in the database:
users: Stores user credentials and profile information.
accounts: Stores account details such as account number, balance, account type, etc.
transactions: Stores transaction history including deposits, withdrawals, and transfers

**Application Structure**
The project follows an MVC (Model-View-Controller) design pattern:
Model: Handles the database interaction through JDBC and includes the classes for Users, Accounts, and Transactions.
View: Built using Java Swing to provide a desktop GUI.
Controller: Manages the interaction between the Model and View and handles the business logic.

