
# **Edu Presence Tracker 🎓📊**  
_A Smart Attendance Management System using Spring Boot 

## **Overview**  
Edu Presence Tracker is a web-based **Attendance Management System** designed to automate and streamline the process of tracking student attendance. Built using **Spring Boot (Java) for the backend** ,this application provides a secure, efficient, and user-friendly platform for **students, faculty, and administrators** to manage attendance records.

## **Features 🚀**  
🚀 Features
Student Module: Manage student records seamlessly.
Subject Module: Handle subject-related operations with ease.
User Module: User authentication and role-based access.
Attendance Module: Keep track of attendance records efficiently.
Service-Oriented Architecture: Encapsulation of business logic in the service layer.
API Testing: Comprehensive API testing using Postman.
Spring Boot & Hibernate: Leveraging modern frameworks for reliability and performance.

### 🔹 **Technology Stack**  
- **Frontend**: Angular, TypeScript, Bootstrap  
- **Backend**: Java, Spring Boot, Spring Security, Hibernate  
- **Database**: MySQL  
- **Authentication**: JWT (JSON Web Token)  

## **Installation & Setup 🛠️**  
### **Backend (Spring Boot)**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/edu-presence-tracker.git
   ```
2. Navigate to the backend folder:  
   ```bash
   cd backend
   ```
3. Configure **application.properties** (MySQL credentials).  
4. Run the application:  
   ```bash
   mvn spring-boot:run
   ```

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
