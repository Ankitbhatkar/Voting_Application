# 🗳️ Voting Web Application -- Online Voting System

A **full-stack online voting management system** built with **Spring
Boot** and **HTML/CSS/JavaScript**. The application enables
administrators to create elections, register candidates, allow voters to
cast votes securely, and view real-time results.

------------------------------------------------------------------------

## ✨ Features

-   Create and manage elections
-   Register voters and candidates
-   Secure voting mechanism
-   Real-time vote counting
-   Automatic result calculation
-   Simple and responsive user interface
-   RESTful backend APIs

------------------------------------------------------------------------

## 🏗️ System Architecture

Frontend (HTML/CSS/JS) → Spring Boot REST APIs → MySQL Database

------------------------------------------------------------------------

## 🧰 Technology Stack

**Backend:** Java, Spring Boot, Spring Data JPA, REST API\
**Frontend:** HTML, CSS, JavaScript\
**Database:** MySQL\
**Tools:** Maven, Git, GitHub, Postman

------------------------------------------------------------------------

## 📁 Project Structure

    src/main/java/in/scalive/votezy
     ├── controller
     ├── service
     ├── repository
     ├── entity
     ├── dto
     └── exception

    src/main/resources
     ├── static
     │   ├── css
     │   ├── js
     │   ├── index.html
     │   ├── voting.html
     │   ├── candidates.html
     │   ├── voters.html
     │   └── results.html
     └── application.properties

------------------------------------------------------------------------

## ⚙️ Setup Instructions

### Clone the Repository

``` bash
git clone https://github.com/Ankitbhatkar/Voting_Application.git
```

### Navigate to Project Directory

``` bash
cd Votezy
```

### Configure Database

Update `application.properties`:

``` properties
spring.datasource.url=jdbc:mysql://localhost:3306/votezy_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### Build the Project

``` bash
./mvnw clean package -DskipTests
```

### Run the Application

``` bash
java -jar target/votezy-0.0.1-SNAPSHOT.jar
```

### Access the Application

    http://localhost:8080/index.html

------------------------------------------------------------------------

## 🚀 Future Enhancements

-   User authentication (JWT)
-   Role-based access control
-   Admin analytics dashboard
-   Mobile responsive UI
-   Cloud deployment

------------------------------------------------------------------------

## 👨‍💻 Author

**Ankit Bhatkar**\
Computer Science Engineer \| Java & Full‑Stack Developer

GitHub: https://github.com/Ankitbhatkar

------------------------------------------------------------------------

⭐ If you like this project, give it a star!
