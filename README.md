# ATMmachine-
his project is a console-based ATM simulation system written in Java. It demonstrates how object-oriented programming (OOP) concepts like classes, objects, and methods can be used to build a simple real-world banking application.
# 🏧 ATM Java Project

A simple **ATM simulation program** written in Java that demonstrates the use of classes, objects, and control structures.

---

## 🚀 Features

- 💰 Deposit money  
- 💸 Withdraw money  
- 👀 View account balance  
- 🔁 Menu-driven console interface  



The ATM program allows a user to:

*  Deposit money into their account
*  Withdraw money from their account (only if sufficient balance is available)
*  Check their current account balance
*  Exit the system safely

It is completely **menu-driven**, meaning the user interacts with the program through numbered options.
The code also performs **basic error checking** — such as rejecting negative amounts and handling insufficient balance.

---

###  Concepts Used

* Classes and Objects (`BankAccount` and `ATM`)
* Methods and Access Modifiers
* Constructors
* Conditional Statements (`if`, `else`)
* Loops (`do-while`)
* User Input using `Scanner`

---

###  How It Works

1. The program starts by creating a bank account with an initial balance (e.g., ₹25,000).
2. The user is shown a list of options: deposit, withdraw, check balance, or exit.
3. Based on the user’s choice, the appropriate method from the `BankAccount` class is called.
4. The process continues until the user chooses to exit.

---

###  Example Output

''
🏧 Welcome to the ATM System!

========= ATM MENU =========
1. Deposit Amount
2. Withdraw Amount
3. View Balance
4. Exit
Enter your choice: 1
Enter amount to deposit: 2000
✅ Successfully deposited: 2000.0

========= ATM MENU =========
1. Deposit Amount
2. Withdraw Amount
3. View Balance
4. Exit
Enter your choice: 3
💰 Current Balance: 27000.0
''


Learning Outcome

This project helps beginners understand:

* How to build Java applications using OOP principles.
* How to manage user input and perform validations.
* How to structure console-based applications logically.
