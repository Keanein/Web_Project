# Web-Based Attendance Management System

A **Web-Based Attendance Management System** developed as a course project for **Web Systems and Technologies**.  
This system automates event attendance recording for the College of Science Student Council (CSSC) and replaces manual attendance sheets with a secure, database-driven solution.

---

## 🚀 Features
- Admin-only authentication
- Event creation and management
- Student attendance recording (AM / PM sessions)
- Edit and delete attendance records
- Attendance report generation
- Export reports to Excel / PDF
- Centralized MySQL database storage

---

## 🛠️ Tech Stack
- **Backend:** Java, Spring Boot  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** MySQL  
- **Server:** Spring Boot Embedded Tomcat  

---

## 🗄️ Database Setup
- This repository includes the database file **`db.sql`**
- Import `db.sql` into your MySQL server
- Locate the configuration file at: attendance-backend\src\main\resources\application.properties
- Edit the following values based on your local database:

spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD

The system will function properly after importing the database and updating the credentials.

---

## ▶️ Running the Project (Local Only)
1. Open the project in **IntelliJ IDEA**
2. Import `db.sql` into **MySQL**
3. Update database credentials in `application.properties`
4. Ensure **MySQL** is running
5. Run the **Spring Boot application**
6. Open a browser and go to: http://localhost:8080/LoginPage.html

⚠️ This project runs **locally only** and is not deployed online.

---

## 📝 Code Documentation
- All **backend Java classes** include meaningful inline comments
- All **frontend files (HTML, CSS, JavaScript)** include clear and descriptive comments
- Comments were written by the project members to improve readability, understanding, and maintainability of the code

---

## 📌 Scope & Limitations
- Academic use only
- Authorized admins only
- Event attendance management only
- Requires local database and server

---

## 👥 Team Members
### Backend
- Keanu Andrie G. Alabado  
- Airene M. Golondrina  

### Frontend
- Micheree Kian Grefiel  
- Jatomie Jonaly Bantayan  

---

## 🎓 Course Information
- **Subject:** Web Systems and Technologies  
- **Project Type:** Web-Based Information System  
- **Purpose:** Academic Requirement
