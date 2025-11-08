# Exp-2: Library Management System

##  AIM
To study, design, and understand the working of a **Library Management System** using UML concepts by identifying the actors, use cases, and functionalities involved in managing library resources.

---

## SOFTWARE REQUIREMENTS SPECIFICATION (SRS)

### 1. Introduction
The **Library Management System (LMS)** is designed to automate the management of a library’s daily activities such as book issuing, returning, catalog management, and maintaining user records. It ensures efficiency, accuracy, and accessibility for both library staff and users.

### 2. Purpose
The main purpose of this project is to simplify the process of managing books, users, and transactions in a library by developing a digital model that ensures fast operations and data consistency.

### 3. Scope
This system includes:
- Managing library resources like books, journals, and magazines  
- User authentication and record maintenance  
- Issuing and returning of books  
- Fine calculation for overdue books  
- Maintaining an organized digital catalog of all books  

---

### 4. Functional Requirements
- **Book Registration:** Add new books and related details into the system.  
- **User Registration:** Add new members (students, staff, etc.) into the database.  
- **Book Issue:** Issue a book to a registered member if it’s available.  
- **Book Return:** Record the return of a book and calculate any late fee if applicable.  
- **Search Books:** Allow users to search books by title, author, or category.  
- **View Catalog:** Display all available books in the library.  
- **Fine Management:** Automatically calculate fines for overdue returns.  

---

### 5. Non-Functional Requirements
- **Security:** Only authorized users can access or modify the system data.  
- **Performance:** Operations like searching and issuing should be processed quickly.  
- **Reliability:** The system should prevent data loss and maintain transaction integrity.  
- **Usability:** Simple and intuitive interface for users and administrators.  
- **Availability:** The system should remain accessible during library hours with high uptime.  

---

### 6. System Actors
- **Librarian:** Manages book records, user registrations, and transactions.  
- **Member (Student/Staff):** Searches, borrows, and returns books.  
- **Administrator:** Maintains the overall system, user roles, and database integrity.  

---

### 7. Use Cases
The primary use cases of the system include:
1. Register New User  
2. Add/Update Book Details  
3. Issue Book  
4. Return Book  
5. Search Book  
6. Calculate Fine  
7. Generate Reports  
8. Manage System Settings (Admin)  

Each use case describes how an actor interacts with the system to complete a specific library operation.

---

# DIAGRAMS:

## Use Case:
![UseCaseDiagram1](https://github.com/user-attachments/assets/a6b8a0df-3bdd-4070-9bd9-b37f7fb5564f)


## Class Diagram:
![ClassDiagram1](https://github.com/user-attachments/assets/527c963a-4316-4863-8145-5906113587bc)


## Sequence Diagram:
![SequenceDiagram1](https://github.com/user-attachments/assets/5a78ce64-9d99-4c1b-a32e-faf98e8b4354)


## Communication Diagram:
![CommunicationDiagram1](https://github.com/user-attachments/assets/6b54bebe-a8ef-4762-aea5-21676988a63f)


## Activity Diagram:
![ActivityDiagram1](https://github.com/user-attachments/assets/800f66a6-c806-4837-aa41-a67879966646)


## Package Diagram:
![PackageDiagram1](https://github.com/user-attachments/assets/3806c7f5-a0f3-43e9-9611-4a9c065b2184)



# RESULT:
The **Library Management System** effectively demonstrates how software can automate and manage a library’s core operations. It shows how different actors such as the librarian, members, and admin interact within the system. The model improves efficiency, reliability, and accessibility, making it ideal for modern library environments.
