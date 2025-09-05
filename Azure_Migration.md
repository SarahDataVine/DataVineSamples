# Access to Azure SQL Migration

## Project Overview
This project involved migrating an existing Microsoft Access database to Azure SQL in order to enable multi-user support, improve performance, and future-proof the system for growth. The database supported invoicing, payroll, and job management processes for a small business.

## Challenges
- The Access back end was limited to single-user or shared-file access, causing frequent conflicts.  
- Performance slowed as data volume grew, especially when multiple users accessed reports.  
- There was no centralized backup or disaster recovery strategy.  

## Solution
- Exported tables from Access and rebuilt the schema in Azure SQL.  
- Normalized tables and renamed legacy columns for consistency.  
- Added primary keys, indexes, and rowversion columns to support concurrency.  
- Rebuilt calculated fields and queries in T-SQL to improve reporting speed.  
- Linked the Access front end to Azure SQL through ODBC for seamless user access.  
- Set up scripts for user installation and automated backups through Azure.  

## Results
- Enabled true multi-user support with improved stability and performance.  
- Reduced reporting time by moving calculations from Access into optimized SQL queries.  
- Provided a reliable backup and recovery solution through Azure Storage.  
- Improved scalability, allowing the system to grow without needing major rework.  

## Tools & Technologies
- Microsoft Access (front end)  
- Azure SQL Database (back end)  
- SQL Server Management Studio (SSMS)  
- VBA, batch scripting for deployment  
- Azure Automation for backups  

---
