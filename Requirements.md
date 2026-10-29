# Application Project: Requirements Specification
## Project Title: GlamBook – Beauty Salon Management System

### 1. Customer Statement of Requirements

**Core Purpose**

GlamBook is a web application designed to help beauty salons manage appointments and services more efficiently. Customers will be able to view available beauty services, check prices, and book appointments online instead of calling or messaging the salon. Salon owners will also be able to manage appointments and update their services.

**Scope of the Application**

**In-Scope (First Iteration):**
- Displaying salon services and prices.
- Allowing customers to book appointments.
- Allowing customers to view and cancel appointments.
- Allowing salon owners to manage appointments and services.
- Storing appointment and customer information.

**Out-of-Scope (Future Iterations):**
- Online payments.
- Automated appointment reminders.
- Customer reviews and ratings.

### 2. Requirements Specification

**Functional Requirements**

- **FR-1 (Service Listings):** The system must display available beauty services, their prices, and descriptions.
- **FR-2 (Appointment Booking):** Customers must be able to book appointments by selecting a service, date, and available time.
- **FR-3 (Appointment Management):** Customers must be able to view and cancel their appointments.
- **FR-4 (Admin Management):** Salon owners must be able to view appointments and add or update salon services.
- **FR-5 (Data Storage):** The system must save customer information and appointment records.

**Non-Functional Requirements**

- **NFR-1 (Usability):** The website must be simple and easy to navigate.
- **NFR-2 (Performance):** The website should load its main pages within three seconds under normal conditions.
- **NFR-3 (Security):** Customer information must be protected, and administrative features must only be accessible to authorized salon staff.

### 3. Data and Storage Blueprint

**Data Input Mechanism**

GlamBook will collect information through forms on the website. Customers will enter their names, contact information, preferred services, and appointment dates. Salon owners will enter service information, prices, and available appointment times.

**Database and Storage Solution**

**Storage Technology:** SQLite relational database.

SQLite will store customer details, salon services, and appointment records. It is a good option for this project because it is lightweight, easy to use, and works well with Python.

The database will contain three main tables:

- **Customers:** Customer ID, name, email, and phone number.
- **Services:** Service ID, service name, description, and price.
- **Appointments:** Appointment ID, customer ID, service ID, date, time, and status.

### 4. Agile Product Backlog

| ID | User Story | Priority |
|---|---|---|
| US-1 | As a customer, I want to view salon services and prices so that I can choose a service. | High |
| US-2 | As a customer, I want to book an appointment online so that I can reserve a time that works for me. | High |
| US-3 | As a customer, I want to view and cancel appointments so that I can manage my bookings. | Medium |
| US-4 | As a salon owner, I want to manage services and appointments so that I can keep my business organized. | High |
| US-5 | As a salon owner, I want customer and appointment records saved so that I can access them when needed. | High |
