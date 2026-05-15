🩺 **Policy Management System**
A Spring Boot-based Hospital Management System designed to efficiently manage hospital operations including patient records, doctor information, appointments.


**💻 Tech Stack**
Layer	-> Technology
Language ->	Java
Framework ->	Spring Boot
Build Tool ->	Maven
ORM	Spring Data -> JPA
Database ->	MySQL
Code Simplifier ->	Lombok
Dependency ->	Spring Web


🔰 **Features**
👉 Patient registration and management
👉 Doctor information system
👉 Appointment booking and tracking
👉 Department-wise organization
👉 Admin and user roles (extendable)
👉 RESTful APIs for integration
👉 MySQL database integration

🗃️ **Project Structure**
hospital-management-system/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.hms/
│   │   │       ├── controller/
│   │   │       ├── entity/
│   │   │       ├── repository/
│   │   │       ├── service/
│   │   │       └── HospitalManagementSystemApplication.java
│   │   └── resources/
│   │       ├── application.properties
│   │       └── data.sql (optional)
├── pom.xml
└── README.md

✅** Prerequisites**
• Java 24 
• Maven
• MySQL Server

🔌** Example Endpoints** Example Endpoints
• HTTP Method	Endpoint	Description
• GET	/patients	List all patients
• POST	/patients	Register a new patient
• GET	/doctors	List all doctors
• POST	/appointments	Book a new appointment HTTP Method	Endpoint	Description
• GET	/patients	List all patients
• POST	/patients	Register a new patient
• GET	/doctors	List all doctors
• POST	/appointments	Book a new appointment

