# 🏦 Bank System (OOP Project)

A Java-based banking system implemented with **Object-Oriented Programming (OOP)** principles.  
This project provides a simple but extendable desktop banking application with **GUI (Swing)** and **database support (JDBC)**.

---

## 📑 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Architecture & Design](#architecture--design)
- [Technologies & Dependencies](#technologies--dependencies)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Database Schema](#database-schema)
- [Testing](#testing)
- [Known Issues & Limitations](#known-issues--limitations)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 📖 Overview

This project simulates the **core functionality of a banking system**.  
Users can log in, check balances, deposit, withdraw, transfer money, and change passwords, all through a simple **Java Swing GUI**.

The design demonstrates **clean OOP structure**, with separation between business logic, GUI, and database persistence.

---

## ✨ Features

- 🔐 **User Authentication** (login/logout, password change)  
- 💰 **Balance Management** (view, deposit, withdraw)  
- 🔄 **Money Transfers** between accounts  
- 🖥️ **Swing GUI** with multiple windows (login, dashboard, transactions)  
- 🗄️ **Database-backed persistence** using JDBC  
- 🧩 **Modular OOP design** (Account, User, Transaction, Services, DAO, etc.)

---

## 🏗 Architecture & Design

- **Entities / Models** → `Account`, `Transaction`, `User`  
- **Business Logic Layer** → Services handle deposits, withdrawals, transfers, and validations  
- **GUI Layer** → Java Swing forms for interaction  
- **Data Access Layer (DAO)** → JDBC connection for CRUD operations  
- **Error Handling & Validation** → Input checks and exceptions  

---

## ⚙️ Technologies & Dependencies

- **Java (JDK 8+)**  
- **Java Swing** (GUI)  
- **JDBC** (database connectivity)  
- **MySQL / SQLite** (or any JDBC-compatible DB)  

---

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shehab-Hegab/Bank-System-OOP-project.git
   cd Bank-System-OOP-project

# Bank-System
Program for banking transactions (Withdrawal, Money Transfer, Deposition).

• The Project is implemented using OOP Concepts to handle these transactions.

• It has some other features like Changing account password and see your current balance.

•	Its GUI is implemented using Java Swing library.

•	It's supported by a database

Note: In case you want to use the database so you have to upload database file (accounts.SQL) to localhost for connecting before running the program


https://user-images.githubusercontent.com/77173710/154792060-0e4738e3-097f-49db-8f4d-8a24ab205638.mp4

