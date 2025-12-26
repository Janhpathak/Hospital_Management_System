🏥 Hospital Management System (HMS)

📖 Overview

The Hospital Management System (HMS) is a Java-based database application developed to automate and manage hospital operations such as patient records, doctor information, appointments, and billing.

The system replaces manual record-keeping with a structured, secure, and scalable software solution, making hospital workflows more efficient and reliable.

🎯 Key Goals

Digitize hospital data management

Reduce paperwork and operational errors

Provide fast and secure data access

Apply core DBMS and Java concepts in a real-world system

🚀 Features

Patient Management – Register, update, and view patient records

Doctor Management – Store and manage doctor details

Appointment Scheduling – Maintain appointment information

Billing System – Handle billing and payment records

Database Integration – Reliable data persistence using MySQL

Modular Design – Clean separation of logic and data access

🛠️ Tech Stack
Category	Technology
Language - Java
Database - MySQL
Connectivity -	JDBC
IDE -	IntelliJ IDEA / Eclipse
Architecture -	Modular (DAO-based)


🗂️ Project Structure
HOSPITAL-MANAGEMENT-SYSTEM

<img width="742" height="353" alt="Screenshot 2025-12-24 at 10 51 12 PM" src="https://github.com/user-attachments/assets/6c04189f-c310-46e3-b1e8-a4e2b45faf76" />





⚙️ Setup & Installation


1️⃣ Clone the Repository

<img width="737" height="63" alt="Screenshot 2025-12-24 at 10 45 22 PM" src="https://github.com/user-attachments/assets/6f4658b0-1bc8-4043-b2f6-0a0c9a7d616e" />

2️⃣ Database Setup
Open MySQL
Create a database
Import hospital.sql

3️⃣ Configure JDBC
Update database credentials in the JDBC connection file:

<img width="765" height="88" alt="Screenshot 2025-12-24 at 10 45 57 PM" src="https://github.com/user-attachments/assets/a7a7a8e5-2a85-410b-8f3a-510b00cd98dc" />

4️⃣ Run the Application
Open the project in IntelliJ IDEA / Eclipse
Run the Main class



🔐 Security Considerations
Uses structured SQL queries
Can be extended with encryption & access control
Designed to support HIPAA/GDPR-ready EMR modules


📈 Future Enhancements
GUI using JavaFX / Swing
Web version using Servlets & JSP
Electronic Medical Records (EMR)
Role-based access control (Admin, Doctor, Staff)
Cloud deployment (AWS / Azure / GCP)
Microservices architecture for scalability
