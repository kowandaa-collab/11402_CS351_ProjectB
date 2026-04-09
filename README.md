# Project B - CSV Mini Database and Query Engine

## Project Overview

This project involves implementing a lightweight, in-memory mini database system that can load, parse, and query CSV (Comma-Separated Values) files. The system functions as a simple relational database engine, allowing users to perform SQL-like queries on tabular data stored in CSV format without requiring external database software.

## Objectives

The primary goals of this project are to:

1. **CSV File Parsing** — Implement robust parsing of CSV files to load data into an in-memory data structure with proper handling of delimiters, quotes, and data types.

2. **Data Storage** — Develop an efficient in-memory data model to represent tables with rows and columns, supporting multiple simultaneous datasets.

3. **Query Engine** — Build a query processor capable of executing basic database operations including:
   - SELECT operations with column filtering
   - WHERE clause filtering and conditional logic
   - Basic JOIN operations between tables
   - Aggregation functions (COUNT, SUM, AVG, MIN, MAX)
   - ORDER BY and GROUP BY clauses
   - LIMIT and OFFSET for result pagination

4. **Query Parsing** — Create a parser to interpret SQL-like query strings and translate them into executable operations.

5. **Result Management** — Format and return query results in a structured manner for display or further processing.

## Key Features

- **Multi-file support** — Load and maintain multiple CSV files simultaneously
- **Flexible querying** — Support a subset of SQL operations tailored for CSV data
- **Data type inference** — Automatically detect and handle various data types (strings, integers, floats, dates)
- **Error handling** — Gracefully handle malformed CSV files and invalid queries
- **Performance efficiency** — Optimize query execution for reasonable dataset sizes
- **User-friendly interface** — Provide simple commands or API for loading files and executing queries

## Technical Requirements

- Implement core data structures for table representation
- Develop a lexer and parser for query interpretation
- Design efficient algorithms for filtering, joining, and aggregating data
- Handle edge cases and provide meaningful error messages
- Support transaction-like operations where applicable

## Deliverables

1. Functional CSV parser
2. In-memory database engine with support for basic SQL operations
3. Query processor with comprehensive error handling
4. Documentation and usage examples
5. Test suite validating core functionality
