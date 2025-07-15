# ✈ Airport Database Management System

A fully functional relational database system designed to manage various aspects of airport operations including flight schedules, passenger details, crew assignments, and more. Built using PostgreSQL and managed with pgAdmin 4.

## 📌 Project Features

- *Database Design & ER Modeling*
  - Structured schema to handle flight scheduling, crew management, passenger records, and airport logistics.
  - Entities include Flights, Passengers, Crew, Airlines, Terminals, and more.
  - Relationships mapped with proper foreign key constraints and referential integrity.

- *Normalization*
  - Tables normalized up to 3NF.
  - Redundancies eliminated and data consistency ensured through normalization proofs.

- *Query Execution & Validation*
  - Implemented real-world use cases such as:
    - Retrieving upcoming flights for a passenger.
    - Viewing assigned crew for a flight.
    - Searching flights by destination, date, or airline.
  - Complex SQL queries tested and validated using pgAdmin 4.

## 🛠 Tools & Technologies

- *PostgreSQL* – SQL-based database engine
- *pgAdmin 4* – GUI tool for database design, query execution, and monitoring
- *ERD* – Entity Relationship Diagrams created using dbdiagram.io / Draw.io
