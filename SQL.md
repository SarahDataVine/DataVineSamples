# SQL Portfolio – Sarah Lawrence

Examples of my SQL development work, including schema design, computed columns, and reporting queries. These samples are drawn from real-world database projects, with sensitive data removed or anonymized.

## Contents

### 1. [**SQL Development Sample**](SQL_Development_Sample_Sarah_Lawrence.pdf)
A documented example of adding **computed columns** to a SQL Server table to support custom business logic and reporting.  
- Includes use of `PERSISTED` computed columns for performance and indexing.  
- Demonstrates logic for completion month, supply budget, adjusted scheduling, and priority scoring.

### 2. [**DropPKAddRowVer.sql**](DropPKAddRowVer.txt)
A schema update script for an invoice line item table.  
- Drops and redefines the primary key.  
- Adds an identity column for unique row identification.  
- Creates a computed column (`TotalForLine`) for line totals.  
- Adds a `ROWVERSION` column to support optimistic concurrency.  

### 3. [**Sample Queries**](Sample%20Queries.txt)
A set of example reporting queries showing SQL fluency:  
- Revenue by customer (last 12 months).  
- Running totals with window functions.  
- Average invoice turnaround time.  
- Top 5 products by sales.  
- Jobs scheduled in the next 30 days.

---

These examples illustrate both **database architecture work** (schema design, migration steps) and **analytical reporting** (queries, aggregations, KPIs). Together, they show my ability to support both the technical foundation and the business-facing side of data systems.
