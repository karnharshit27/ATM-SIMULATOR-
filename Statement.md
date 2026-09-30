Problem Statement:-

Traditional ATM systems provide essential banking services such as
checking account balances, depositing and withdrawing money, and viewing
transaction details. However, for a simple project implementation, there
is a need for a lightweight ATM simulation that demonstrates these basic
banking operations in a clear and organized way. The project addresses
this need by providing a menu-driven ATM system that allows a user to
securely log in using a PIN and perform common account-related
operations. The system also stores account information and transaction
records so that changes to the account can be maintained between program
executions.

Scope of the Project:-

The project covers the implementation of a basic ATM simulation using
Python and a JSON data file for storing account information and
transaction details. The system provides PIN-based login verification
and allows the user to access the ATM menu after successful
authentication. Within the available functions, the user can check the
current balance, deposit money, withdraw money, view transaction
history, view account information, and change the PIN. Deposit and
withdrawal operations update the account balance and record the
corresponding transaction with its date and time. The system also
handles invalid amounts, insufficient balance, incorrect PIN entries,
and account locking after three unsuccessful login attempts.

Target Users:-

The target users are individuals who need a simple interface for
performing basic ATM operations in a simulated banking environment. The
project is also suitable for students and learners who want to
understand how an ATM system can be implemented using Python, including
concepts such as user authentication, account management, balance
handling, transaction recording, input validation, and data storage. The
system is designed for users who require only the basic banking
operations provided within the project.

High-Level Features:-

The system provides PIN-based authentication before allowing access to
the ATM menu. A user can check the current account balance, deposit
money, and withdraw money while the system validates the entered amounts
and checks for sufficient balance before completing a withdrawal. Each
successful deposit or withdrawal is recorded in the transaction history
with the transaction type, amount, and date and time. The system also
allows the user to view stored account information and change the
existing four-digit PIN after verifying the current PIN. For security,
the system permits up to three incorrect PIN attempts and locks the
account after the limit is reached. Account and transaction data are
stored in a JSON file so that updated information can be saved and
loaded when the program runs.
