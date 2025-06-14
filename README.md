# 📚 Library Management System — Java Console Application  

A beginner-friendly **Library Management System** built using **Core Java** concepts. This **console-based application** allows users to register, log in, view/search/borrow/return books, and provides admins with control over book and user data.  

---

## 🧠 Key Concepts Used  
- **Object-Oriented Programming (OOP)**  
- **Java Collections Framework** (ArrayList, HashMap, etc.)  
- **File I/O or In-Memory Storage** (based on your design)  
- **Abstraction & Interfaces**  
- **Exception Handling**  
- **Modular & Layered Design**  

---

## ✨ Features Overview  

### 🔐 Authentication System  
- Register as a new user  
- Login as a user or admin  
- Exit application  

### 👤 Normal User Dashboard  
Once logged in as a regular user, the following features are available:  

| Feature      | Description |
|-------------|------------|
| 📚 **View Books** | List of books with Serial No, Name, Author, Publisher, Year, Copies |
| 🔍 **Search Book** | Search for a book by name |
| 📖 **Borrow Book** | Borrow a book by entering its Book ID |
| 📥 **Return Book** | Return a borrowed book using its Book ID |
| 📋 **My Books** | View dashboard of all currently borrowed books |
| 🔓 **Logout** | End current session |

### 🛠 Admin Dashboard  
Login as admin grants access to additional management features:  

| Feature      | Description |
|-------------|------------|
| ➕ **Add Book** | Add new book records with full details |
| 📚 **View Books** | View all available books in the system |
| 👥 **View Users** | View registered users and their borrowed book records |
| 🔓 **Logout** | End admin session |

---

## 🗂 Project Structure
- LibraryManagementSystem
  - Manager
    - LibraryManager.java **(Handles core operations)**
    - LoginManager.java **(Manages login and registration logic)**
  - Model
    - Book.java **(Book entity with attributes and methods)**
    - User.java **(User entity: admin/user, borrowed books, etc.)**
  - Main.java **(Entry point for app flow)**
  - README.md **(Project documentation)**
---

## 🗂 Sample Book Table  

| **ID**  | **Book Name**           | **Author**       | **Publisher**     | **Year** | **Copies/Total** |
|--------|-----------------------|---------------|----------------|------|---------------|
| 1001   | Introduction to Java   | John Smith    | Sun Publishers  | 2020  | 3 / 5 |
| 1002   | Data Structures        | Alice Johnson | TechPress      | 2018  | 1 / 2 |
| 1003   | Operating Systems      | Mark Wilson   | Core Books     | 2019  | 0 / 4 (Out of Stock) |

---

## 📈 Future Enhancements  

✅ **Password Protection** — Store passwords securely using basic encryption or hashing (e.g., SHA-256).  

💾 **Persistent Storage** — Replace in-memory lists with simple file storage using FileReader/FileWriter or BufferedReader/Writer.  

🗃 **Basic Database Integration** — Introduce JDBC and connect to a local MySQL or SQLite database to store books and user records permanently.  

🖥 **Simple GUI** — Implement a basic user interface using Java Swing or JavaFX for a better user experience.  

📊 **Borrowing Summary (Dashboard)** — Show simple stats like total borrowed books, overdue books (manually calculated), etc.  

📎 **Book Categorization / Genre Filtering** — Add a `"genre"` field to books and allow users to filter by genre (e.g., Science, Literature, Tech).  

---

## 👨‍💻 Author  
Developed with ❤️ by **Himanshu Yadav**  

