# Debt Management System

A console-based C++ application that allows users to manage personal lending records. The system supports account registration, debt tracking, and data persistence through file handling.

## 📌 Features

* **Account Management**

  * Register new users
  * User login with credential verification
* **Debt Management**

  * Add new debt records
  * View borrower's debts
  * Sort debts by due date or amount
  * Remove settled debts
* **Data Persistence**

  * Save and load debt and account data using `.txt` files

## 🛠️ Built With

* C++ Standard Library (iostream, fstream, vector, string, etc.)
* Object-oriented design using structs and modular functions
* File I/O for persistent data storage

## 📂 File Structure

* `main.cpp` - Main application logic
* `accounts.txt` - Stores user credentials
* `USERNAME.txt` - Stores debt records for each user (created dynamically)

## 💡 Usage

Upon launching the program, users can:

1. **Register** - Create a new account.
2. **Log In** - Access their debt dashboard.
3. **Add/View/Sort/Remove Debts** - Manage individual borrower records.
4. **Save** - Persist changes to text files.

## 📊 Example Flow

```text
1. Register or Login
2. Add a borrower's name, contact, amount, interest rate, and due date
3. View and sort debts
4. Save debts to file
5. Logout or exit the system
```

## 📌 Notes

* Each user has a separate file (`username.txt`) to store their debts.
* Interest is calculated based on the percentage input during debt addition.
* Data is not saved automatically if the program is forcefully closed.
* Account information is only saved when you exit the program properly through the provided menu.
* To avoid data loss, always use the "Exit" option in the main menu after registering or modifying account details.
