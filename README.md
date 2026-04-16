# Joins
** University Join Lab**

This SQL project demonstrates the core concepts of relational database management using Structured Query Language (SQL). The *University Join Lab* system organizes university data into related tables and ensures data integrity through constraints such as primary keys, foreign keys, and validation rules. The project ensures that invalid data, such as negative marks or incorrect references, is not accepted.

---

### **Key Principles of Database Design**

The project achieves proper database design by:

**Data Integrity**
Uses primary keys and foreign keys to maintain accurate and consistent relationships between Department, Student, Course, and Enrollment tables.

**Data Validation**
Applies constraints such as NOT NULL, UNIQUE, and CHECK to ensure only valid data (e.g., marks between 0–100, credit greater than 0) is stored in the database.

**Relationship Management**
Establishes relationships between tables using foreign keys (STUDENT ↔ DEPARTMENT, COURSE ↔ DEPARTMENT, ENROLLMENT ↔ STUDENT/COURSE).

**Controlled Data Access**
Uses SQL JOIN operations to retrieve and combine related data from multiple tables in a structured way.

**Structured Design**
Demonstrates a well-organized relational schema that reduces redundancy and improves data efficiency.

---

### **Program Demonstration Steps**

The execution of the project highlights key database operations:

* Four tables (DEPARTMENT, STUDENT, COURSE, ENROLLMENT) are created to represent the system.
* Sample data is inserted into all tables, including departments, students, courses, and enrollments.
* SQL JOIN queries are used to combine and display related information.
* LEFT JOIN is used to include unmatched records for complete data analysis.
* Aggregate functions (COUNT, AVG, MIN, MAX) are applied for statistical analysis.
* GROUP BY and HAVING clauses are used to generate summarized results such as department-wise and course-wise reports.
* ORDER BY and LIMIT are used to identify top-performing students.
* LIKE operator is used for pattern-based searching of student names.
* Constraints ensure data reliability by preventing invalid entries and maintaining consistency across tables.
* Overall, structured SQL queries are used to efficiently manage and analyze university data.

