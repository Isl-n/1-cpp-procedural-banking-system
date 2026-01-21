# C++ Console Banking System (Procedural)

A simple console-based banking system written in **procedural C++** (not OOP).  
Client data is stored in a text file and the program provides a menu-driven interface to manage clients and perform basic transactions.

---

## ✨ Features

- List all clients in a formatted table
- Add new clients (prevents duplicate account numbers)
- Find, update, and delete clients
- Deposit and withdraw
- Show total balances for all clients
- File-based persistence using `Clients.txt` (records separated by `#//#`)

---

## 🗂️ Data Storage

- File: `Clients.txt`
- Format per line:
  `AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance`

---


## 📝 Notes

- The program will create/use `Clients.txt` in the same directory as the executable.
- This project is intentionally procedural to practice functions, file I/O, and menu-driven program flow.
- Uses `system("cls")` and `system("pause>0")` (Windows console behavior).
---


## 🚀 Build & Run

Compile with any C++ compiler:

```bash
g++ main.cpp -o BankSystem
./BankSystem
```