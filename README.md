# 🏥 Hospital Management System  
### Object-Oriented Programming (C++)

## 📌 Overview

The Hospital Management System is a console-based application developed using C++ that manages core hospital operations including:

- Patient records
- Doctor management
- Appointment scheduling
- Medical information tracking
- Human Resources administration

The system is built using Object-Oriented Programming principles and demonstrates structured class design, file handling, and system modularity.

---

## 🚀 Features

### 👤 User Management
- Registration and login system
- Role-based access (Patient, Doctor, HR)
- Password update functionality
- Mobile number update functionality

---

### 🩺 Patient Management
- Book appointments
- Cancel appointments
- View scheduled appointments
- Access personal medical information

---

### 👨‍⚕️ Doctor Management
- View assigned patients
- Access patient medical records
- Editable job titles (by HR)
- Doctor schedule management

---

### 🏢 Human Resources Module
- Add new doctors
- Remove doctors
- View all doctors by specialization
- View all registered patients

---

### 🧪 Lab Technician Module
- Create patient medical records
- Validate medical input values
- Calculate BMI automatically
- Generate medical condition report

---

## 🧠 OOP Concepts Implemented

- **Inheritance**  
  - Patients and Doctors inherit from the User class

- **Aggregation**  
  - Patient has Medical Information  
  - Patient has Appointments  
  - Doctor has Schedule  

- **Abstraction**  
  - Separate header (.h) and implementation (.cpp) files  

- **Encapsulation**  
  - Getter and setter methods for class attributes  

---

## 🛠 Technologies Used

- C++
- Object-Oriented Programming
- File handling
- Header & implementation file structure
- Console-based interface

---

## 🏗 System Architecture

Main classes include:

- `User`
- `Patient`
- `Doctor`
- `Medical_info`
- `Appointments`
- `Schedule`
- `Human_Resources`
- `Labtech`

Each module is designed with clear responsibilities and structured interaction between components.

---

## 👩‍💻 My Contribution

This project was developed collaboratively as part of a University project.

My contributions included:

- Implementing the Human Resources class
- Integrating HR functionality into the main program
- Implementing validation logic
- Supporting system integration and testing
