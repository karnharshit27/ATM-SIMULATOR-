# ATM-SIMULATOR-
ATM Simulation System

Overview of the Project:-

The ATM Simulation System is a Python-based console application that simulates the basic operations of an ATM. The program uses a JSON file to store account information, balance, PIN status, and transaction history.

After successful PIN verification, the user can access the ATM menu and perform banking operations such as checking the balance, depositing money, withdrawing money, viewing transaction history, viewing account information, and changing the PIN. The account data is saved back to the JSON file so that changes are retained when the program is run again.

The main Python program handles the ATM operations, while atm_data.json is used for storing the account data and transaction records. The program also includes PIN-attempt control and locks the account after three incorrect PIN attempts.

Features:-

PIN Login and Verification: The user must enter the correct PIN to access the ATM. The system allows a maximum of three incorrect attempts before locking the account.

Check Balance: Displays the current available account balance.

Deposit Money: Allows the user to enter a deposit amount, updates the balance, and records the transaction with its date and time.

Withdraw Money: Allows the user to withdraw money when sufficient balance is available. The withdrawal is recorded in the transaction history.

Transaction History: Displays previous deposits and withdrawals along with their date, time, transaction type, and amount.

Account Information: Displays the account holder's name, account number, phone number, and email address.

Change PIN: Allows the user to change the current PIN after verifying the old PIN. The new PIN must contain exactly four digits and must be confirmed.

Account Locking: The account is automatically locked after three consecutive incorrect PIN attempts.

Data Persistence: Account balance, PIN changes, account status, and transactions are saved in atm_data.json.

Technologies/Tools Used:-

Python: Used as the main programming language for implementing the ATM simulation and its functions.

JSON: Used to store account details, balance, PIN information, account lock status, and transaction history.

datetime module: Used to record the date and time of deposits and withdrawals.

os module: Used to check whether the JSON data file exists before loading the account data.

VS Code / Python Terminal: Can be used to write, edit, and run the project.

Steps to Install & Run the Project:-

Install Python on the computer if it is not already installed.

Place the following files in the same project folder:

atmsimulation.py

atm_data.json

Open the project folder in VS Code or open a terminal in the project folder.

Run the following command:

python atmsimulation.py

The program will display the ATM welcome screen and ask for the account PIN.

Enter the PIN stored in the account data file to log in.

After successful login, the ATM menu will be displayed and the required operation can be selected.

Instructions for Testing:- 

Run the program using

python atmsimulation.py

Test Login: Enter the correct PIN and check that the message Login successful! is displayed.

Test Incorrect PIN: Enter an incorrect PIN and verify that the program shows the number of remaining attempts.

Test Account Lock: Enter an incorrect PIN three times and verify that the account becomes locked.

Test Balance: Select Check Balance and verify that the displayed balance matches the balance stored in atm_data.json.

Test Deposit: Select Deposit Money, enter a valid positive amount, and verify that the balance increases and a new deposit appears in the transaction history.

Test Withdrawal: Select Withdraw Money, enter an amount within the available balance, and verify that the balance decreases and the withdrawal is recorded.

Test Insufficient Balance: Try to withdraw an amount greater than the available balance and verify that the program displays Insufficient balance.

Test Transaction History: Select Transaction History and verify that the recorded deposits and withdrawals are displayed with their date and time.

Test Account Information: Select Account Information and verify that the stored account details are displayed.

Test Change PIN: Select Change PIN, enter the current PIN, provide a new four-digit PIN, confirm it, and verify that the PIN is updated in the JSON data.

ScreenShots :- 

<img width="330" height="182" alt="image" src="https://github.com/user-attachments/assets/fc7393f0-21dd-4b93-89ed-11f78e2481ae" /><img width="318" height="267" alt="image" src="https://github.com/user-attachments/assets/c862d364-ee17-416d-8a4c-455d8c0caa55" /><img width="301" height="316" alt="image" src="https://github.com/user-attachments/assets/7482f25c-5e75-4bc6-a2f6-9122a908e7e8" /><img width="317" height="362" alt="image" src="https://github.com/user-attachments/assets/80f6f6d6-5365-4bc5-b8ad-a25cb6274f0f" /><img width="306" height="352" alt="image" src="https://github.com/user-attachments/assets/50993058-a297-4c9d-a360-46f1990a058a" /><img width="403" height="393" alt="image" src="https://github.com/user-attachments/assets/79aa67e2-e425-4f3f-95ba-08864828c8be" /><img width="391" height="406" alt="image" src="https://github.com/user-attachments/assets/173dc5ab-799f-4de6-8c67-0ede3696f2af" /><img width="333" height="412" alt="image" src="https://github.com/user-attachments/assets/8d0470ad-2480-4bb7-9ad6-4ae266995126" /><img width="317" height="327" alt="image" src="https://github.com/user-attachments/assets/128c0f99-1d6e-489e-a98c-c8dce20f61c2" />

Test Exit: Select Exit and verify that the program displays the exit message and closes the ATM menu.

END
