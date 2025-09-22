# Library Management System - Database Schema

This repository contains the database schema for a simple Library Management System. This project was completed as part of Task 1 for the SQL Developer Internship at Elevate Labs.

## Project Overview

The objective of this project is to design and create a relational database schema for a library. The schema defines the structure for storing information about books, authors, members, transactions, and more.

### Key Features of the Schema
* Tracks books, including titles, publishers, and categories.
* Manages information about authors and links them to books.
* Handles library member data and membership status.
* Records book borrowing and returning transactions.
* Allows for book reservations.

## Files in this Repository

1.  **`LibraryDB.sql`**: The main SQL script containing all the `CREATE TABLE` statements and relationship definitions (foreign keys) for the PostgreSQL database.
2.  **`Library_ERD.png`**: The Entity-Relationship Diagram (ERD) that provides a visual representation of the database schema and the relationships between the tables.

## How to Use

1.  Ensure you have a PostgreSQL server and a tool like `pgAdmin` installed.
2.  Create a new database (e.g., `LibraryDB`).
3.  Open the `LibraryDB.sql` script in your SQL tool.
4.  Execute the script to create all the tables and define their relationships.

## Tools Used
* **Database**: PostgreSQL
* **Tool**: pgAdmin 4