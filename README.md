📚 Student Database Management System
A colorful and responsive Student DBMS project built with Spring Boot, MySQL, and a beautiful HTML/CSS/JavaScript frontend. This system supports full CRUD operations: Add, Update, Delete, and View Students.

🚀 Features
🎨 Colorful and professional UI

🧑 Add, edit, delete student records

🛢️ Data stored in MySQL database

🔌 REST API with Spring Boot

🌐 Full-stack integration (Backend + Frontend)

🛠️ Tech Stack
| Frontend      | Backend            | Database | Tools                    |
| ------------- | ------------------ | -------- | ------------------------ |
| HTML, CSS, JS | Spring Boot (Java) | MySQL    | Maven, VS Code, IntelliJ |

📂 Project Structure
studentdb/
│
├── src/
│   ├── main/
│   │   ├── java/com/example/studentdb/
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   └── StudentdbApplication.java
│   │   └── resources/
│   │       ├── application.properties
│   │       └── static/index.html
│
├── pom.xml
└── README.md

⚙️ Setup & Deployment
🐳 Prerequisites
  Java 17+
  Maven
  MySQL Server running locally (localhost:3306)
  MySQL database named studentdb

🔧 MySQL Setup
    CREATE DATABASE studentdb;
📦 Build & Run the Spring Boot App
    cd studentdb
    ./mvnw spring-boot:run

This runs your app at:
http://localhost:9090 or http://localhost:9094 (if you changed the port)

📬 API Endpoints
| Method | Endpoint             | Description          |
| ------ | -------------------- | -------------------- |
| GET    | `/api/students`      | Get all students     |
| POST   | `/api/students`      | Add new student      |
| PUT    | `/api/students/{id}` | Update student       |
| DELETE | `/api/students/{id}` | Delete student by ID |


