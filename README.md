# Future Abilities College – Access Database Project

## Overview
This project is a Microsoft Access database system designed for **Future Abilities College** to replace their old spreadsheet-based system.  
It streamlines registration and management of students, staff, courses, classrooms, and units, while enabling leadership to extract, analyze, and report key information efficiently.

The database is normalized up to **Third Normal Form (3NF)** to ensure data integrity, reduce redundancy, and improve query performance.  

---

## Features
- **Student Management** – Register, edit, and delete student records with course enrollment details.
- **Course Management** – Track courses, units, and classroom assignments.
- **Staff & Teaching Assignments** – Manage staff records and link them to teaching units.
- **Classroom Tracking** – Monitor classroom capacities and available equipment.
- **Forms** – User-friendly forms for entering, modifying, and navigating data.
- **Queries** – Predefined queries to retrieve useful insights:
  - Students per course  
  - Units per course  
  - Staff working hours  
  - Teacher-student allocations  
- **Reports** – Printable and structured reports for leadership:
  - Students by Course  
  - Teachers and Their Students  
  - Teachers by Units/Courses  
  - Course Unit Breakdown  
  - Staff Working Hours  

---

## Database Structure

### Tables
- **Students** – Student ID, personal details, contact info, course enrolled.  
- **Courses** – Course ID, course name, number of units, classroom reference.  
- **Units** – Unit ID, unit name, course reference.  
- **Classrooms** – Classroom ID, room number, capacity, equipment availability.  
- **Staff** – Staff ID, personal details, contact info, working hours.  
- **Teaching Assignment** – Links staff to specific units.  

### Relationships
- **Courses ↔ Students**: One-to-many  
- **Courses ↔ Units**: One-to-many  
- **Courses ↔ Classrooms**: Many-to-one  
- **Units ↔ Teaching Assignments**: One-to-many  
- **Staff ↔ Teaching Assignments**: One-to-many  

---

## Implementation
- **Forms**: Graphical interfaces for managing students, staff, courses, and teaching assignments.  
- **Queries**: Extract insights such as student enrollment, units per course, staff working hours, and teacher-student allocation.  
- **Reports**: Present information clearly for non-technical users.  

---

## Technical Details
- **Platform**: Microsoft Access  
- **Normalization**: UNF → 1NF → 2NF → 3NF  
- **Validation**: Implemented in tables for data integrity (primary/foreign keys, text length, yes/no constraints).  
- **Documentation**: Includes data dictionary, ER diagram, implementation plan, and evaluation.  

---

## Maintenance & Evaluation
- **User Documentation**: Forms, navigation menus, and reports make the system intuitive.  
- **Technical Documentation**: ER diagrams, table structures, and validation rules for future developers.  
- **Maintenance**: Database should be updated periodically for new courses, staff, or students.  
- **Evaluation**: Regular reviews ensure the system meets operational needs and scales with growth.  

---

## How to Use
1. Open the database in Microsoft Access.  
2. Start from the **Home Form** for navigation.  
3. Use forms to add, update, or delete records.  
4. Run queries to extract information.  
5. Generate reports for printing or decision-making.  




