# BTO Management System

A command-line-based Build-To-Order (BTO) flat application system designed for managing projects and users across different roles: Applicants, HDB Officers, and HDB Managers.

---

## Features

-User Authentication
  - NRIC and password-based login.
  - Role-based access and operations.

-Project Management
  - Managers can create new BTO projects with application dates and flat options.
  - Officers can view assigned projects and handle applications.

-Application System
  - Applicants can view projects, check eligibility, and apply for flats.
  - System checks marital status and age for eligibility.

-Enquiry Management
  - Applicants can create, view, edit, or delete enquiries.
  - Officers and Managers can view and respond to enquiries.

-Password Management
  - Users can change their default password after first login.

-Reports & Actions
  - Managers can view project statistics and officer assignments.

---

## Technologies Used

- Java 17+
- Console-based UI
- OOP Concepts: Inheritance, Encapsulation, Polymorphism
- Java Collections (e.g., `ArrayList`)
- Custom Input Handling via ConsoleHelper

---

## How to Run

1. Download or Clone this repository.
2. Open in any Java IDE like IntelliJ, Eclipse, or BlueJ.
3. Run the Main.java file to launch the system.
4. Use one of the sample users below to log in.

---

## Sample Users

You can use these accounts to log in:

### ➤ Applicant
For manager : Jessica,S5678901G,26,Married,password (She manages Acacia Breeze)
For Applicant : Rachel,S3456789E,25,Single, password (Ineligible)
James,T2345678D,30,Married,password (Eligible)
For officer : David,T1234567J,29,Married,password
Test with the project: Acacia Breeze,Yishun,2-Room,2,350000,3-Room,3,450000,2/15/25,3/20/25,Jessica,3,"Daniel,Emily"
