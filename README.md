# CODETECHINTERNSHIP-Task-2
Name: ANUSHA TIRUMALA
Company: CODTECH IT SOLUTIONS
ID: CT12DS312
Domain: Java Programming
Duration: May to July 2024
Mentor: G.Sravani
Overview of the Online Banking System Java Program
Purpose:
The purpose of this Java program is to simulate an online banking system where users can log in, manage their accounts, perform banking operations (such as deposit, withdraw, transfer), and view account details.

Components and Functionality:
User Interface:

Uses Scanner for user input to simulate a command-line interface (CLI) for interacting with the banking system.
Provides options for users to log in, exit the system, and performs banking operations once logged in.
User Management:

Allows users to log in using their username and password.
Once logged in, provides access to user-specific banking functionalities.
Account Management:

Supports management of multiple accounts per user.
Users can perform operations like depositing funds, withdrawing funds, transferring funds between accounts, and checking account balances.
Data Persistence:

Simulated in-memory storage of user accounts and transactions using Java classes.
Error Handling:

Includes basic error handling for invalid inputs and ensures operations are performed safely (e.g., checking for sufficient funds before performing a withdrawal).
User Experience:

Provides clear prompts and messages to guide the user through interactions with the banking system.
Ensures security by validating user credentials and handling sensitive operations like withdrawals and transfers carefully.
Detailed Breakdown:
Initialization:

Sets up a Scanner object to read user input from the console.
Initializes a placeholder for the current user (currentUser) to manage sessions.
User Login:

Prompts users to enter their username and password.
Authenticates users against predefined credentials (for simplicity, this can be hardcoded or simulated).
Main Menu:

Displays options for logging in or exiting the system.
Uses a switch statement to handle user choices:
Allows users to log in (case 1) or exit (case 2).
Banking Operations:

Once logged in, presents a menu of banking operations:
Deposit funds into an account.
Withdraw funds from an account.
Transfer funds between accounts.
View account balance.
Account and Transaction Handling:

Manages user accounts and their associated transactions.
Uses classes like User, Account, and Transaction to encapsulate data and operations related to banking activities.
Error Handling and Validation:

Validates user inputs to prevent errors (e.g., ensuring numeric input for amounts).
Checks for sufficient funds before allowing withdrawals or transfers.
User Interface Flow:

Guides users through each step with clear prompts and responses, ensuring a user-friendly experience.
