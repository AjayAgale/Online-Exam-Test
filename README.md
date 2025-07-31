#  Online-Exam-Test-beginner

An end-to-end Online Exam Test System for beginner-level learning and development, built using Angular, Spring Boot, and MySQL. This project allows admins to create and manage quizzes, users to attempt tests, and both to view results.

🚀 Features
👨‍🏫 Admin Panel
Create / Update / Delete Tests

Add / Edit / Remove Questions

View all test results by users

Track individual user performance

View admin profile info

🧑‍🎓 User Panel
Register / Login securely

Attempt assigned tests

View result immediately

Responsive and user-friendly UI

🛠️ Tech Stack
Layer	Technology
Frontend	Angular 17+, HTML5, SCSS
Backend	Spring Boot, Spring Security
Database	MySQL
API Tool	Postman (for testing APIs)
Authentication	JWT-based login system.

Installation & Setup:

Backend (Spring Boot)

Clone the repository

Go to backend directory

Set database connection in application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/onlinequiz
spring.datasource.username=root
spring.datasource.password=your_password

Run the project with:
./mvnw spring-boot:run

Frontend (Angular)

Go to frontend directory

Run:
npm install

Start Angular app:
ng serve

Open in browser:
http://localhost:4200/

Default Credentials:

Admin:
Email: uday@gmail.com
Password: uday@135

User:
Email: user@example.com
Password: user123
