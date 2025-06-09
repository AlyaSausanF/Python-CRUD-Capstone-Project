# Simple CRUD Application for Student Data
Purwadhika Data Science Capstone Project Module 1: Python
[Presentation decK link](https://www.canva.com/design/DAGUpjd1t3Y/BSSRk8SQ-fy9fWlw1pnagA/view?utm_content=DAGUpjd1t3Y&utm_campaign=designshare&utm_medium=link&utm_source=viewer) 

**Introduction**

This project is a simple CRUD (Create, Read, Update, Delete) application using Python designed to manage student data. It incorporates role-based access control and additional features to enhance usability and data management. The application allows administrators and students to interact with the data based on their roles.

**Features**

**1. Core CRUD Operations**

**Create:**
- Admin can add new student data, including NIS (Student Identification Number), Name, Date of Birth, City of Residence, Email, and Graduation Status.

**Read:**
- Admin can view all student data.
- Students can view their data.
- Sorting options are available for admin to organize data by:
    - NIS
    - Name
    - Date of Birth
    - City of Residence
    - Email

**Update:**
- Admin can update student data with the following options:
  - Edit the entire row of data.
  - Edit specific columns: Name, Date of Birth, City of Residence, or Email.
- Students can edit their data.

**Delete:**
- Admin can delete student data.

**2. Role-Based Access Control**

**Admin:**
- Full access to all CRUD features.
- Can view and manage all student data.

**Student:**
- Limited access to view and edit their data.

**3. Advanced Features**

**Sorting:**
- Admin can sort student data for easier navigation and organization based on various fields.

**Selective Data Editing:**
- Admin can update specific fields (e.g., Name, Date of Birth) or entire rows in the database.

**Backup and Restore:**
- Deleted student data is backed up.
- Admin can restore previously deleted student records when needed.

**Graduation Status Automation:**
- Admin can automatically set a student's graduation status by entering the student’s NIS.
