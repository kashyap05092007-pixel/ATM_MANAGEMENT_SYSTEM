# ATM_MANAGEMENT_SYSTEM



# 🏦 ATM Management System (C++)

A simple **console-based ATM Management System** developed using **C++** and **Object-Oriented Programming (OOP)** concepts.
This project simulates basic banking operations like balance checking, deposit, withdrawal, and transaction history.

---

## 📌 Introduction

The ATM Management System is designed for learning purposes to understand how real-world ATM systems work in a simplified way.
It demonstrates the use of core **OOP principles** in C++.

---

## 🎯 Features

* 🔐 Secure PIN Authentication
* 💰 Check Account Balance
* 💵 Deposit Money
* 💸 Withdraw Money
* 📜 Transaction History
* 🚫 Prevents overdrawing
* 📋 Menu-driven interface

---

## 🧠 OOP Concepts Used

* **Encapsulation** → Data hiding using private members
* **Abstraction** → Interface using abstract class (`IATM`)
* **Inheritance** → `ATM` class inherits from `IATM`
* **Polymorphism** → Virtual functions (withdraw method)

---

## 🏗️ Project Structure

```
ATM_Management_System/
│── main.cpp
│── README.md
```

---

## ⚙️ How It Works

1. User enters a 4-digit PIN
2. System verifies PIN (3 attempts allowed)
3. Displays ATM menu
4. User selects operation
5. System processes request
6. Output is displayed

---

## 💻 Sample Output

```
----- OOP MINI ATM -----
1. Check Balance
2. Deposit
3. Withdraw
4. History
5. Exit
```

---

## 🚀 How to Run

### 🔧 Requirements

* C++ Compiler (G++ / CodeBlocks / VS Code)

### ▶️ Steps

```bash
# Compile the program
g++ main.cpp -o atm

# Run the program
./atm
```

---

## 📊 Code Highlights

* Uses **classes and objects**
* Implements **abstract class (interface)**
* Maintains **transaction history using vector**
* Secure login with **PIN verification**

---

## 📌 Future Improvements

* Add multiple user accounts
* File handling for data storage
* GUI version (using Qt or other libraries)
* Database integration

---

## 👨‍💻 Author

 Patel Kashyap Nikunjkumar
🎓 B.Tech CSE (1st Year)
🏫 JG University






