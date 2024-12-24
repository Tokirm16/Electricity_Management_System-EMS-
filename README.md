# Electricity Management System (EMS)

This repository contains the **Electricity Management System (EMS)** project, developed using **Spring Boot** for the backend and **Angular** for the frontend.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
  - [Customer Features](#customer-features)
  - [Admin Features](#admin-features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
  - [Backend (Spring Boot)](#backend-spring-boot)
  - [Frontend (Angular)](#frontend-angular)
- [Usage](#usage)
- [Screenshots](#screenshots) *(Optional, add screenshots here if available)*

---

## Project Overview

The **Electricity Management System (EMS)** is a comprehensive platform designed to streamline the management of electricity bills and customer complaints. It features two main user roles:
1. **Customer**: A registered user who can manage their electricity bills and complaints.
2. **Admin**: A privileged user who oversees customer management, bill generation, and complaint resolution.

The repository includes two `.zip` files:
- **ems-angular.zip**: Contains the frontend code built with Angular.
- **ems-springboot.zip**: Contains the backend code built with Spring Boot.

---

## Features

### Customer Features
- **Registration & Login**: Customers can register and log in to the platform.
- **Dashboard**: Access a personalized dashboard with the following functionalities:
  - Register new complaints.
  - View the status of previous complaints.
  - View bill history.
  - Pay electricity bills online.
  - Update profile details such as address, password, etc.
- **Profile Management**: Update personal information, such as contact details.

### Admin Features
- **Dashboard**: Access an admin-specific dashboard with the following functionalities:
  - Add new customers/consumers to the system.
  - Generate and assign bills for each customer.
  - View and manage complaints registered by customers.
  - Edit customer details, such as address or contact information.
  - Soft-delete customers from the system (removal without complete data deletion).
  - View comprehensive customer details, including bills, complaints, and the customer list.

---


---

## Technologies Used

- **Backend**: Spring Boot, MVC Model, Derby
- **Frontend**: Angular, TypeScript, Bootstrap
- **Tools**: Ecllipes, Visual Studio Code, Postman, Git
- **Build Tools**: Maven (for Spring Boot), Angular CLI (for Angular)

---

## Installation and Setup

### Backend (Spring Boot)
1. Extract the `ems-springboot.zip` file.
2. Open the project in your IDE (e.g., IntelliJ IDEA or Eclipse).
3. Configure the Derby database connection in the `application.properties` file:
   ```properties
   spring.datasource.url=jdbc:derby:memory:ems_db;create=true
   spring.datasource.driver-class-name=org.apache.derby.jdbc.EmbeddedDriver
 

