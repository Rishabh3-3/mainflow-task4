# Task 4 – Java Swing Login System with MySQL Integration

This project is part of my internship at MainFlow Services and Technologies Pvt. Ltd and focuses on integrating a Java Swing application with a MySQL database, along with building a professional homepage UI using NetBeans.

---

## 🚀 Features

- ✅ **MySQL Integration** using JDBC
- ✅ **DatabaseConnection.java** class to manage DB connectivity
- ✅ **LoginForm.java** for user authentication (basic UI)
- ✅ **Homepage.java** designed with Swing GroupLayout
- ✅ Functional **Logout** button linking back to login screen

---

## 🛠️ Tech Stack

- **Java** (JDK 17)
- **Swing GUI** (NetBeans IDE)
- **MySQL** (via JDBC Connector)
- **NetBeans** (Java Ant Project)

---

## 📌 Steps Implemented

### 1. MySQL Setup
- Created a local database `user_auth`
- Added sample users with hashed passwords

### 2. JDBC Configuration
- Downloaded `mysql-connector-java-8.x.xx.jar`
- Added it to project libraries via NetBeans

### 3. Database Connection Class
- `DatabaseConnection.java` uses `DriverManager.getConnection()`
- Verified successful connection with console output

### 4. UI Design in NetBeans
- Created `Homepage` using JFrame Form
- Added:
  - Title Label (`"Welcome to the Homepage"`)
  - Greeting Label (`"Hello, User!"`)
  - Buttons: View Profile, Settings, Logout
- Used `GroupLayout` for vertical alignment and padding

### 5. Functionality
- `Logout` button closes homepage and opens `LoginForm`

---

## ✅ How to Run

1. Clone or download the repo
2. Open in NetBeans (as a Java Ant Project)
3. Make sure MySQL server is running and credentials match
4. Press **Shift + F6** to run `Homepage.java` (ensure `LoginForm.java` exists)
5. You’ll see console output:  


---

## 🧩 Folder Structure

/src
├── DatabaseConnection.java
├── LoginForm.java
├── Homepage.java
└── Homepage.form


---

## 🙏 Acknowledgements

Thanks to team at @MainFlow Services and Technologies Pvt. Ltd for the opportunity and guidance throughout this task.

---


