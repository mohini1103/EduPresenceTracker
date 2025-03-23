📘 EduPreTracker – Attendance Management System 🎓

  EduPreTracker is a Spring Boot-based backend application for an Attendance Management System. It simplifies and automates attendance tracking for students and faculty, ensuring secure authentication, role-based access, and attendance submission.
  
  🚀 Features
Student Module: Manage student records seamlessly.
Subject Module: Handle subject-related operations with ease.
User Module: User authentication and role-based access.
Attendance Module: Keep track of attendance records efficiently.
Service-Oriented Architecture: Encapsulation of business logic in the service layer.
API Testing: Comprehensive API testing using Postman.
Spring Boot & Hibernate: Leveraging modern frameworks for reliability and performance.

  🛠️ Technology Stack
Backend Framework: Spring Boot
ORM: Hibernate
Database: SQL (e.g., MySQL, PostgreSQL)
API Testing: Postman
Languages: Java
Tools: Maven, Git, Eclipse IDE

  📂 Project Structure

  
EduPresenceTracker/
├── src/main/java/com/edupretracker/
│   ├── controller/
│   │   ├── StudentController.java
│   │   ├── SubjectController.java
│   │   ├── UserController.java
│   │   └── AttendanceRecordController.java
│   ├── service/
│   │   ├── StudentService.java
│   │   ├── SubjectService.java
│   │   ├── UserService.java
│   │   └── AttendanceService.java
│   ├── dao/
│   │   ├── StudentRepository.java
│   │   ├── SubjectRepository.java
│   │   ├── UserRepository.java
│   │   └── AttendanceRepository.java
│   ├── model/
│   │   ├── Student.java
│   │   ├── Subject.java
│   │   ├── User.java
│   │   └── AttendanceRecord.java
│   └── utils/
│       └── CustomUtils.java
├── src/main/resources/
│   ├── application.properties
│   └── data.sql
└── pom.xml
