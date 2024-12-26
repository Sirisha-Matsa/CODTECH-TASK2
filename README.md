# CODTECH-TASK2

Name: Sirisha Matsa

Company: CODTECH IT SOLUTIONS

ID: CT08DQC

Domain: SQL

Duration: DEC-2024 TO JAN-2025

Mantor: NEELA SANTOSH KUMAR

# OVERVIEW OF THE PROJECT:

Project: Student Management System

# OBjetive:

To create a simple library database that helps manage books, members, and borrow records. It makes it easy to add or update details, track which books are borrowed, check availability, and keep data accurate, making library operations smooth and efficient.

  
# Key Components:

  Tables
  BOOKS: Stores details about books in the library, including the title, author, genre, publication year, and quantity available.
  MEMBERS: Contains information about library members, such as their name, email, mobile number, and joining date.
  TRANSACTIONS: Tracks the borrowing and returning of books by members, linking books and members through foreign keys.
  
# Functionalities:
  
  Data Insertion:

  INSERT INTO commands populate the BOOKS, MEMBERS, and TRANSACTIONS tables with initial sample data, simulating real-world    scenarios like book additions and member registrations.
  
  Data Modification:

  Updating Data:
      Adjust book quantities (e.g., when restocking).
      Update member details, such as their mobile number or ID.
  Deleting Data:
      Remove specific books or members based on conditions.
  Data Retrieval:
      View all books or members (SELECT *).
      Filtered queries to fetch specific records (e.g., books with a particular ID or borrowing history of a member).
      Join queries to retrieve complex relationships, such as the borrowing history of a member or the current status of           borrowed books.  
  Key Queries:
    Borrowing History of a Member:
        Uses a JOIN between TRANSACTIONS and BOOKS to show which books a specific member borrowed, along with borrowing and           return dates.
    Currently Borrowed Books:
      Filters the TRANSACTIONS table for records where RETURNDATE is NULL, indicating the book has not been returned.
      
# Key Features:

Primary Keys: Ensure unique identification of each record in BOOKS, MEMBERS, and TRANSACTIONS tables.

Foreign Keys: Establish relationships between tables:
  BOOKID links TRANSACTIONS to BOOKS.
  MEMBERID links TRANSACTIONS to MEMBERS.
  
Constraints:
  NOT NULL ensures critical fields are always populated.
  UNIQUE prevents duplicate entries for fields like email and mobile number.

# OUTPUT:

<img width="238" alt="image" src="https://github.com/user-attachments/assets/beee77ff-8a90-4ff4-8d72-5067737ac262" />

