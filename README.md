# 🏧 Mini ATM Machine

A simple console application that lets users open virtual bank accounts, securely access them with PINs, and manage money just like at an ATM. Great for OOP and encapsulation practice!

---

## ✨ Features

- **Create bank accounts** with a 4-digit PIN
- **Authenticate** securely using PINs
- **Check account balance**
- **Deposit money** (with validation)
- **Withdraw money** (with overdraft protection)
- **Change account PIN** securely
- **Logout and exit safely**
- **Encapsulation:** All PINs and balances are securely handled

---

## 🚀 How to Run

1. Make sure Python is installed (3.x recommended).
2. Save the code as `atm.py`.
3. Open your terminal or command prompt.
4. Run: `python atm.py`

---

## 💡 Example Session

--- Welcome to Mini ATM Machine ---:

1. Create Account

2. Access Account

3. Exit
Choose an option (1-3): 1
Enter account number: 12345
Set a 4-digit PIN: 1234
Account created successfully.

4. Create Account

5. Access Account

6. Exit
Choose an option (1-3): 2
Enter account number: 12345
Enter PIN: 1234
Authentication Successful.

--- ATM Menu ---:

1. Check Balance

2. Deposit

3. Withdraw

4. Change PIN

5. Logout
Enter your choice(1-5): 2
Enter deposit amount: 100
Deposited 100. New Balance: 100.0

---

## 🛠 How It Works

- Each account uses the `BankAccount` class, managing secure PINs and balances.
- The `ATM` class manages multiple accounts, authentication, and the main menu.
- All actions (deposit, withdraw, PIN changes) have validation and error handling.

---

## 📄 License

MIT License — free to use, modify, and share.

---

Try your hand at secure banking logic and OOP with this ATM simulation!
