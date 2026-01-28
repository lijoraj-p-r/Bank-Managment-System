
# Bank Management System (Java Console App)
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/db7c9cd4-3fd8-4314-bee0-7695af332847" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1af3712a-a974-4170-8d62-cb5bf57ab923" />

A Java console application that simulates a **simple banking system** using **text files for data persistence**. This project supports creating accounts, depositing, withdrawing, balance checks, login, and transaction history — all stored and retrieved from `.txt` files.

It’s a great demonstration of **file handling**, **OOP basics**, **console UI**, and **data persistence without a database**, making it ideal for a portfolio or resume.

---

## 🧠 Project Overview

This application mimics basic bank operations such as:

* **Creating a new bank account**
* **Logging in using account credentials**
* **Deposits and withdrawals**
* **Balance inquiries**
* **Recording transactions to text files**
* **Keeping user data and credentials in text files**

All data is stored in a local `db` folder using `.txt` files (e.g., `credentials.txt`, `balanceDB.txt`, `userDB.txt`) for persistence. ([GitHub][1])

---

## 🛠 Features

✅ **Text file based storage** — No database required
✅ **Account creation & login**
✅ **Deposit & withdraw functionality**
✅ **Balance inquiry**
✅ **Transaction record keeping**
✅ **Incremental account number generation using last saved entry**
✅ **Modular design using multiple Java classes**

---

## 📌 Why This Project?

This project shows you:

✔️ How to read from and write to text files in Java
✔️ How to model bank operations without a database
✔️ How to design a real‑world console UI logic
✔️ How to use `Scanner`, `File`, and `FileWriter/Reader` classes effectively
✔️ Basic account and transaction management logic

---

## 💻 How It Works (Workflow)

1. **Launch the app**
2. Choose to either **create an account** or **login**
3. Enter details such as name, account information, and initial balance
4. The system will:

   * Write user info into `userDB.txt`
   * Write credentials into `credentials.txt`
   * Write starting balance into `balanceDB.txt`
5. Once logged in, users can:

   * **Deposit** money
   * **Withdraw** money
   * **Check balance**
   * **Review transaction history**

Data is read and written using Java file I/O operations to persist between executions. ([GitHub][1])

---

## 🗂 Repository Structure

```
Bank‑Managment‑System/
├── db/
│   ├── credentials.txt
│   ├── balanceDB.txt
│   ├── userDB.txt
│   └── other text files
├── src/
│   ├── Main.java
│   ├── Login.java
│   ├── Creation.java
│   ├── Transaction.java
│   ├── BalanceEnquiry.java
│   ├── AccountDetails.java
│   └── Deletion.java
├── .gitignore
├── README.md
└── .project / .classpath (Eclipse config)
```

---

## 📁 Example Output

```
Welcome to Bank Management System!

1. Login
2. Create Account
3. Exit

Enter choice: 2
Enter your name: John Doe
Account created successfully! Your account no is: 1001

Login with your account number and password
```

```
Logged in!
1. Deposit
2. Withdraw
3. Balance
4. Transaction History
```

---

## 🧩 Core Concepts Used

| Concept                     | Demonstrated                     |
| --------------------------- | -------------------------------- |
| File Handling               | Reading and writing `.txt` files |
| OOP                         | Classes for different bank tasks |
| Input Validation            | Ensuring correct user input      |
| Incremental Account Numbers | By reading last saved entry      |
| Modular Code                | Separate classes for logic       |

---

## 🚀 How to Run

1. **Clone the repository**

```
git clone https://github.com/lijoraj-p-r/Bank-Managment-System
```

2. **Open in Eclipse**

   * Import as an existing Eclipse project
   * Ensure the `db` folder is in project root

3. **Run `Main.java`**

   * Follow the console prompts

---

## 🧪 Future Enhancements

Here are some ideas to make it even better:

✔️ Add user authentication with hashed passwords
✔️ Convert to a GUI application using Swing or JavaFX
✔️ Store data in a real database (e.g., MySQL)
✔️ Add exception handling for I/O errors
✔️ Extend transaction history reporting

