Library System Design Activity
This repository contains a simple Library System conceptual design activity for Software Design & Architecture.
Overview
The activity focuses on identifying important classes in a library system and defining their attributes, methods, relationships, and abstraction decisions.
Main Classes
- Book
- BookCopy
- Member
- Librarian
- Loan
- Reservation
- Fine
- Library
Topics Covered
- Candidate conceptual classes
- Attributes and methods
- Abstraction decisions
- Software objects
- Class relationships
- Basic system modeling
Main Relationships
- Member → borrows → Loan
- Loan → is for → BookCopy
- Book → has → BookCopy
- Member → makes → Reservation
- Loan → may create → Fine
- Librarian → manages → Library
File
Library_System_Group_Activity.pdf

This activity demonstrates how real-world library operations can be represented using software concepts and conceptual classes.
