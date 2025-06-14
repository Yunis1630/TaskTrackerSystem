# Task Tracker System (Console-based Java Application)

This is a **console-based Task Tracker system** developed in Java. The application supports **role-based access** for Admins and Members, and stores all user and task data in files.

---

## 🔧 Features

### 🔐 Login System
- Prompts for username and password at launch
- Authenticates from `users.txt`
- Displays different menus based on user role (Admin or Member)

### 👤 Admin Capabilities
- Add new users (username, password, role)
- Delete users
- Assign tasks to members (`tasks.txt`)
- View all tasks and progress statuses

### 👨‍💻 Member Capabilities
- View assigned tasks
- Mark tasks as completed

---

## 📁 File Structure

- `users.txt` – Stores login credentials and roles
- `tasks.txt` – Stores task descriptions and statuses
- `src/` – Java source files (Main.java, AdminMenu.java, etc.)

---

## 💡 Technologies Used

- Java (Console-based)
- File I/O operations
- Custom Exception handling
- Basic Object-Oriented Programming (OOP)

---

## 🚀 Getting Started

To run the project:

1. Clone the repository
2. Compile using your preferred IDE (e.g. IntelliJ IDEA)
3. Run the `Main.java` file

---

## 📌 Author

- GitHub: [Yunis1630](https://github.com/Yunis1630)
