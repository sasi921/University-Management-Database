# University Management Database

An academic **Oracle SQL / relational database design** project for managing core university operations including students, academic records, departments, courses, enrollment, advisors, financial aid, events, internships, faculty, and alumni outcomes.

## Project Overview

The project was designed to address common university data-management problems such as duplicated records, inconsistent information across departments, limited accessibility, difficulty tracking alumni and internships, and fragmented event management.

The database centralizes this information into a relational model and demonstrates the full database-design lifecycle: business rules, user requirements, EER modeling, normalization to 3NF, Oracle table creation, sample data insertion, and analytical SQL queries.

## Key Entities

- Student
- Advisor
- AcademicRecords
- Department
- Faculty
- Courses
- EnrollmentOffice
- FinancialAid
- Scholarship
- Internship
- StudentOrganization
- Events
- Alumni
- Company
- Higher_Studies
- Entrepreneur
- CSE / ECE / Mech / Electrical department subtypes

## SQL Concepts Demonstrated

- Primary and foreign keys
- One-to-many and many-to-many relationships
- Oracle `VARCHAR2`, `NUMBER`, and `DATE` types
- `JOIN` operations across multiple tables
- Filtering with `WHERE`, `LIKE`, `IN`, `AND`, and `OR`
- Date functions and `TO_DATE`
- Aggregation with `AVG`, `GROUP BY`, and `HAVING`
- Subqueries
- Conditional expressions with `CASE`
- Set operations: `UNION`, `MINUS`, and `INTERSECT`
- Aliases, concatenation, and arithmetic expressions

## Repository Structure

```text
University-Management-Database/
├── README.md
├── sql/
│   ├── schema-and-data.sql
│   └── queries.sql
└── docs/
    └── Final-Report-Team-Project-1.pdf
```

## Running the Project

The SQL is written for **Oracle Database / Oracle APEX**.

1. Open Oracle SQL Developer, SQLcl, or Oracle APEX SQL Workshop.
2. Run `sql/schema-and-data.sql` to create the schema and insert the sample records.
3. Run queries from `sql/queries.sql` to explore the database.

## Academic Scope

This repository preserves the original academic project and demonstrates relational data modeling and SQL skills. It is intended as a portfolio and learning artifact rather than a production university information system.

## Author

**Sasidhar Reddy Velkuri**
