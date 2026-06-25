# Queries — SQL Data Extraction

A collection of SQL scripts and modules for structured data extraction, transformation, and reporting across multiple database schemas.

## Structure

```
Queries/
├── Module1/     # SQL queries for Module 1 schema
├── Module3/     # SQL queries for Module 3 schema
└── SubModel/    # Sub-model specific extraction queries
```

## What's Inside

Each module contains SQL scripts covering:

- **SELECT queries** — data retrieval with filters, joins, and aggregations
- **Data transformation** — reformatting raw data for reporting
- **Subqueries & CTEs** — complex nested query patterns
- **Aggregate reports** — GROUP BY summaries and pivot-style outputs

## Usage

1. Connect to your SQL database (MySQL, PostgreSQL, or SQL Server)
2. Navigate to the relevant module folder
3. Execute the `.sql` files in order (if numbered)

```sql
-- Example: run in your SQL client
SOURCE Module1/extract_data.sql;
```

## Prerequisites

- Any SQL-compatible database (MySQL 5.7+ / PostgreSQL 10+ / SQL Server 2016+)
- A SQL client (MySQL Workbench, pgAdmin, DBeaver, or similar)

## Tech Stack

- **Language:** SQL
- **Compatible with:** MySQL, PostgreSQL, SQL Server
