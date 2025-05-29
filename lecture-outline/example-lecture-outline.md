# Lecture 2: Introduction to SQL Database Schema Design

Duration: 80 minutes [including quizzes and exercises]
Active Delivery: 50 minutes

## Objectives

1. Understand the importance of database schema design.
2. Learn key terminologies: Tables, Attributes, Domains, Tuples, Data Types.
3. Recognize constraints and their significance in schema design.

## Pre-Lecture Setup

  1. Pre-read/Pre-work
    - Basic understanding of databases from Lecture 1 & notes.
  2. Software/Tools Setup
    - MySQL Workbench installed and configured.
  3. Room Setup
    - Projector and whiteboard ready for use.

## Lecture Outline

### 1. Introduction & Warm-Up (5 minutes)

- Objective: Set the stage for understanding schema design.
- Icebreaker: Quick discussion on how students store their personal data (e.g., contacts, notes).
- Guiding Questions:
  - How do you organize your personal data?
  - What challenges do you face in finding specific information?
  - How do databases effectively organize data?
  - Why can't we randomly store data?
- Transition: Explain how these personal data organization challenges relate to database schema design.

### 2. Core DBMS Concepts (50 minutes)

- Objective: Introduce key terminologies and practices of schema design.
- Terms to explain:
  - Tables, Attributes, Data Types, Schema, UML Diagrams, Constraints
- Visual Aids:
  - Diagrams showing tables, rows, columns
  - Visual comparison of schema variations
- Interactive Discussion:
  - Discuss different schema examples (customer data tables)

#### Content Flow

1. Structure of a Database [10 minutes]:

    - Explain the concept of a database schema.
    - Discuss how schemas are like blueprints for databases.

2. Key Terminologies [10 minutes]:

      - Tables: Explain what a table is in a database.
      - Attributes: Define attributes as columns in a table.
      - Data Types: Discuss different data types (e.g., VARCHAR, INT, DATE) and their significance.

3. CHECKPOINT 1: Quiz to assess understanding of key terminologies. [5 minutes]

4. Schema Design Practices [10 minutes]:

      - Explain UML Diagrams and their role in visualizing database structure.
      - Create a simple UML diagram on the board.
      - Explain how to represent tables, attributes, and relationships in UML.

5. Schema Design on MySQL [10 minutes]:

    - Discuss how to create a schema in MySQL Workbench.
    - Discuss the importance of choosing appropriate data types for attributes.
    - Introduce constraints in MySQL.
    - Explain how to define constraints (NOT NULL, UNIQUE, PRIMARY KEY) in MySQL.

6. CHECKPOINT 2: Quiz/Question to assess understanding of key terminologies. [5 minutes]

### 3. Practical Demonstration (Activity 1) (10 minutes)

- Objective: Show practical schema creation.
- Live Coding/Demo: Instructor creates schema on MySQL Workbench.
- Common Pitfalls students might face:
  - Incorrect data types
  - Ignoring constraints

### 4. Summary of Key Concepts (5 minutes)

- Objective: Reinforce key concepts learned today.
- Key Points:
  - Importance of schema design
  - Key terminologies: Tables, Attributes, Data Types
  - Constraints (NOT NULL, UNIQUE, PRIMARY KEY)

### 5. Q&A and Deep Dive for Advanced Topics (10 minutes)

- Objective: Address any questions and explore advanced topics.
- Open floor for student questions.
- Discuss advanced topics like schema normalization and best practices.

## Quizzes & Exercises

### In-class

**Activity 1**: Collaborative Schema Design (10 minutes)

- Students create a Cart schema with attributes and constraints on whiteboard with instructor guidance.

**Checkpoint 1 Quiz**: Key Terminologies (5 minutes)

- Question 1: What is a table in a database?
  - A) A collection of rows and columns
  - B) A type of data
  - C) A programming language
  - D) None of the above

**Checkpoint 2 Quiz**: Schema Design Practices (5 minutes)

- Question 1: What is the purpose of a UML diagram in database design?
  - A) To visualize the database structure
  - B) To write SQL queries
  - C) To store data
  - D) None of the above

**Exercise 1 (Coding)**: Schema Creation (10 minutes)

- Question 1: Create a schema for a “Users” table with the following attributes:
  - UserID (INT, Primary Key)
  - Username (VARCHAR(50), NOT NULL, UNIQUE)
  - Email (VARCHAR(100), NOT NULL, UNIQUE)
  - CreatedAt (DATETIME, NOT NULL)

### Post-class

<-- Post-class quizzes and exercises -->

### Lab Questions

<-- Lab Questions -->

## Extras

- Further Reading:
  - "Database Design for Mere Mortals" by Michael J. Hernandez
  - Online resources on SQL schema design.
