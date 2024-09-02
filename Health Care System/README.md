# Medicare-Hospital-Management-System

The Medicare Hospital Management System is a database project designed to manage patient and staff information, treatments, and departments in a hospital setting. It involves multiple interconnected tables: Patients, Departments, Staff, and Treatments, each serving a specific role in the hospital's database management.

The Patients table stores patient details like name, date of birth (DOB), email, and phone number, with unique constraints on PatientID and Email. The Departments table holds department names such as Cardiology, Neurology, and Orthopedics, each identified by a DepartmentID.

The Staff table records details of the hospital's personnel, such as doctors and nurses, including their role and department affiliation, with foreign keys linking to the Departments table. The Treatments table tracks all treatment records, including treatment dates and costs, while linking patients and staff through foreign keys.

The project uses SQL queries to perform essential operations like inserting data into the tables, updating treatment costs, and deleting records. It also includes complex queries to retrieve detailed information, such as listing treatments along with the patient's and staff's names, grouping patients by total treatment costs, and filtering records based on specific conditions, like staff members who have treated more than three patients.

This system is essential for organizing hospital operations efficiently, ensuring easy access to patient and treatment histories, and providing valuable insights, such as the total cost of treatments for a patient. It demonstrates core SQL functionalities like JOINs, grouping, and subqueries.
