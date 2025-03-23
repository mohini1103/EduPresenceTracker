# **Edu Presence Tracker 🎓📊**  
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
- **Backend**: Java, Spring Boot, Spring Security, Hibernate  
- **Database**: MySQL  
- **Authentication**: JWT (JSON Web Token)  

  📂 Project Structure

  
         EduPresenceTracker/
      ├── src/main/java/com/edupresencetracker/
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

 💻 API Endpoints

### **Student APIs**  
   | Method | Endpoint                  | Description               |
   |--------|---------------------------|---------------------------|
   | **GET**    | `/api/students`           | Get all students          |
   | **GET**    | `/api/students/{id}`      | Get student by ID         |
   | **POST**   | `/api/students`           | Add a new student         |
   | **PUT**    | `/api/students/{id}`      | Update student details    |
   | **DELETE** | `/api/students/{id}`      | Delete student            |

### **Subject APIs**  
   | Method | Endpoint                  | Description               |
   |--------|---------------------------|---------------------------|
   | **GET**    | `/api/subjects`           | Get all subjects          |
   | **GET**    | `/api/subjects/{id}`      | Get subject by ID         |
   | **POST**   | `/api/subjects`           | Add a new subject         |
   | **PUT**    | `/api/subjects/{id}`      | Update subject details    |
   | **DELETE** | `/api/subjects/{id}`      | Delete subject            |
   
   More API details available in the Postman collection.

🧪 Testing with Postman

   Postman was used extensively for API testing.

 🏗️ Architecture
The application is structured into multiple layers:

1. Controller Layer: Handles HTTP requests and responses.
2. Service Layer: Contains business logic.
3. DAO Layer: Data Access Objects for database interactions.
4. Model Layer: Defines the data models.

📖 Getting Started
Prerequisites
JDK 11 or higher
Maven
MySQL or PostgreSQL
Postman (optional)

Steps to Run

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
5. Access the application at http://localhost:8091.
✨ EduPresenceTracker – Empowering Education with Technology! ✨

