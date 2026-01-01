# DMI Rapid - Loan Finance System

## Overview
**DMI Rapid** is a full-stack loan management system designed to streamline loan processing for financial institutions. It allows users to apply for loans, track approval status, and provides admins with analytics to make data-driven decisions.  

- **Frontend:** Angular (TypeScript, HTML, CSS)  
- **Backend:** Java Spring Boot (REST APIs, Spring Security)  
- **Database:** MySQL / PostgreSQL  
- **Authentication:** JWT-based secure login  



---

## Features
- **User Registration & Login:** Secure authentication for customers and admins.  
- **Loan Application:** Users can submit loan requests with all required details.  
- **Loan Status Tracking:** Real-time tracking of loan approval status.  
- **Admin Dashboard:** View, approve, or reject loan applications; analyze loan trends.  
- **Data Analytics:** Interactive charts for loan distribution, approval rates, and trends.  
- **RESTful API:** Backend APIs built with Spring Boot for efficient data management.  

---

## Tech Stack
| Layer       | Technology |
|------------|------------|
| Frontend   | Angular, TypeScript, HTML, CSS, Bootstrap/Material UI |
| Backend    | Java, Spring Boot, Spring Security, REST APIs |
| Database   | MySQL / PostgreSQL |
| Other Tools| JWT, Maven/Gradle, Chart.js / ngx-charts |

---

## Project Structure

DMI-Rapid/
├── backend/ # Spring Boot application
│ ├── src/
│ ├── pom.xml
├── frontend/ # Angular application
│ ├── src/
│ ├── angular.json
├── README.md
└── .gitignore


---

## Installation

### Backend (Spring Boot)

1. Navigate to backend folder:
```bash
cd backend

./mvnw spring-boot:run  # Maven
# OR
./gradlew bootRun       # Gradle


###Frontend (Angular)

1. Navigate to backend folder

cd frontend


Install dependencies:

npm install


Run the Angular app:

ng serve


Open in browser: http://localhost:4200
