💳 New Bank Of India - C++ Bank Management System
A simple console-based banking system built using modern C++ to simulate banking operations such as account creation, deposit/withdrawal, login, and transaction history — with persistent file-based storage.

🚀 Features
Create a bank account with a unique account number

Secure login using account number and password

Deposit and withdraw money

Check account balance

View account details

Transaction history (saved per session)

Data persistence using .txt files

Simple terminal UI with colored text

🛠️ Technologies Used
C++

File Handling (fstream)

Object-Oriented Programming (OOP)

ANSI Escape Sequences for color formatting (Linux/macOS compatible)

📂 Project Structure
bash
Copy
Edit
.
├── main.cpp               # Main program file (your source code)
├── Tasin-Coder-Bank-Of-India.txt   # Stores bank code (used to generate account numbers)
├── *.txt                  # Individual user account files generated after account creation
🧑‍💻 How It Works
Account Creation

Takes personal details and generates a unique account number.

Initial balance is ₹500.

Saves user details to a file: <accountNumber>.txt.

Login

Authenticates using account number and password.

On successful login, provides a menu to deposit, withdraw, view balance, and transaction history.

Data Storage

All account data and transactions are saved in individual text files.

🧪 Sample Usage
bash
Copy
Edit
$ g++ main.cpp -o bankApp
$ ./bankApp
Main Menu:
markdown
Copy
Edit
Welcome to Tasin Coder Bank Of India
--------------------------------------
1. Create Account
2. Login
3. Exit
After Login:
mathematica
Copy
Edit
----------------------------------
 Enter 1 for Deposit Money
 Enter 2 for Withdraw Money
 Enter 3 for Check Balance
 Enter 4 for Account Details
 Enter 5 for All Transaction History
 Enter 6 for Logout
----------------------------------
⚠️ Notes
Linux/macOS only: Uses system("clear") and ANSI escape sequences for colors.

For Windows, change system("clear") to system("cls") and remove or adapt the color functions.

Ensure Tasin-Coder-Bank-Of-India.txt exists with an initial integer (e.g., 101) to avoid account number generation issues.

📌 To Do (Suggestions)
Password encryption

Delete account feature

Support for multiple concurrent users

GUI version using Qt or web-based front-end

🧑‍💼 Author
Deepak Kumar
Bank Management System coded with 💻 in C++
