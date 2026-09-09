# University Management Database — Project Notes

## Introduction

This academic database project models a centralized university management system that supports students, faculty, alumni, advisors, financial-aid staff, student organizations, internship administration, and university administrators.

The original project report identifies several problems with fragmented university data: duplicated and inconsistent records, limited access to important information, difficulty tracking alumni and internships, and inefficient event management. The proposed database centralizes these operations to improve data integrity, accessibility, reporting, and administrative efficiency.

## Business Rules

The project defines rules including:

- Each student has one academic advisor; an advisor may counsel multiple students.
- Students maintain academic records.
- Students enroll in multiple courses.
- Event participation is optional.
- A student may participate in one internship in the project model.
- Alumni status follows graduation.
- Financial aid and scholarships are tracked alongside student obligations.
- Departments offer courses.
- Students belong to a department.
- Faculty members are associated with departments.

## Users

- **Students:** enrollment, records, financial aid, events.
- **Faculty / Advisors:** course and student information for teaching and advising.
- **Administrators:** departments, programs, financial aid, alumni, and reporting.
- **Alumni:** career and university engagement information.
- **Financial Aid Office:** scholarships and student financial support.
- **Department Heads:** faculty and course information.
- **Student Organization Leaders:** event-management information.
- **Internship Office:** internship opportunities and student placements.

## Data Model

The EER model includes Student, Advisor, AcademicRecords, EnrollmentOffice, Courses, Department, Faculty, FinancialAid, Scholarship, Internship, Events, StudentOrganization, Alumni, Company, Higher_Studies, Entrepreneur, and department-specialization tables such as CSE, ECE, Mech, and Electrical.

The project also documents cardinalities such as Advisor–Student one-to-many, Student–Enrollment–Course many-to-many, Department–Course one-to-many, and Alumni specializations for company employment, higher studies, or entrepreneurship.

## Normalization

The project report presents the relations in at least **Third Normal Form (3NF)**, separating major university concepts into dedicated tables connected through primary and foreign keys.

## Oracle APEX Validation

The original report includes screenshots of Oracle APEX `DESC` and `SELECT` output for the schema tables, followed by approximately fifteen query exercises covering single-table retrieval, joins, projections, aliases, concatenation, filters, dates, subqueries, aggregation, `GROUP BY`, `HAVING`, `UNION`, `MINUS`, and `INTERSECT`.

## Files

- `../sql/schema-and-data.sql` — table definitions, constraints, and academic sample records.
- `../sql/queries.sql` — the query set demonstrated in the report.

## Academic Note

This repository preserves the database as an academic portfolio project. The sample data and SQL reflect the submitted coursework and are not presented as a production university information system.
