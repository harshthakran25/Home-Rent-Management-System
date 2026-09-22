# 🏠 Home Rent Management System

> A robust, modular backend engine and relational database management system designed to streamline property leasing, tenant records, and payment tracking.

---

## 📌 Project Overview

Managing rental properties manually often leads to data redundancy, lost payment records, and scheduling conflicts. The **Home Rent Management System** solves this by implementing an end-to-end, data-consistent backend architecture. 

Built using **Python** and **MySQL**, the system couples a normalized relational database schema with an Object-Oriented application layer to handle secure CRUD operations, automated rent calculations, and multi-table transactional integrity.

---

## ⚙️ Key Technical Highlights

* **Normalized Relational Architecture (3NF):** Designed relational schemas enforcing referential integrity (primary/foreign key constraints) across properties, units, tenants, lease contracts, and payment transactions.
* **Secure Database Interaction:** Utilizes `mysql-connector` with strictly parameterized queries to eliminate SQL injection vulnerabilities.
* **Transaction Safety (ACID):** Implements explicit `commit` and `rollback` routines within error-handling blocks to safeguard against incomplete writes during payment processing.
* **Object-Oriented Design (OOP):** Modular separation between database controllers, business logic engines, and data models for clean maintainability.
* **Validation & Edge-Case Testing:** Integrated input validation routines to check for overlapping lease tenures, vacant unit availability, and overdue balance computations.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Database:** MySQL
* **Connector / Driver:** `mysql-connector-python`
* **Core Concepts:** Relational Database Design (3NF), OOP, ACID Transactions, Unit Testing
* **Tools:** VS Code, Git, GitHub
