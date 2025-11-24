# Smart-Data-Manager-A-Java-Based-CRUD-Application
This Java project demonstrates core programming concepts through a simple, modular application that allows users to manage data through add, update, delete, and view operations. It applies OOP principles, clean design, and interactive workflows to connect theory with real-world problem solving.

# Smart Task Scheduler & Productivity Tracker  
*A Java-based offline task manager for students and professionals.*

## ⭐ Overview
The Smart Task Scheduler & Productivity Tracker is a lightweight, console-based Java application designed to help users manage daily tasks efficiently. It allows you to add, delete, view, and complete tasks while also providing productivity analytics.

## 🎯 Features
- Add new tasks with description, priority, and deadline  
- View all tasks  
- Mark tasks as completed  
- Delete tasks  
- Auto-save tasks through serialization  
- Productivity summary  
- Offline and lightweight  
- Fully modular OOP design  

## 🛠️ Technologies Used
- Java (Core Java 8+)  
- OOP  
- Collections (ArrayList)  
- File Handling (Serialization)  
- Exception Handling  
- CLI UI  

## 📂 Project Structure
```
SmartTaskScheduler/
│
├── Main.java
├── Task.java
├── TaskManager.java
├── tasks.dat
└── README.md
```

## 🚀 How to Run
### 1. Clone or download  
```
git clone https://github.com/yourusername/SmartTaskScheduler.git
```

### 2. Compile  
```
javac Main.java
```

### 3. Run  
```
java Main
```

## 📘 How It Works
### Task.java
Represents a task with id, title, description, priority, deadline, and status.

### TaskManager.java
Handles logic: add, delete, update tasks + file saving & loading.

### Main.java
Provides CLI menu.

## 🧪 Sample Output
```
--- SMART TASK SCHEDULER ---
1. Add Task
2. View Tasks
3. Mark Completed
4. Delete Task
5. Summary
6. Exit
```

## 📈 Future Enhancements
- GUI  
- Database storage  
- Notifications  
- Calendar integration  
- CSV/PDF export  

## 📄 License
Free for academic use.
