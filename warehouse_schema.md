# Star Schema

## Overview
A Star Schema is a data warehouse design model where a central fact table is connected to multiple dimension tables. It is called a "star" because of its shape.

## Structure

### Fact Table
The fact table contains measurable data (metrics), such as:
- Sales amount
- Quantity sold

### Dimension Tables
These provide context to the data, such as:
- Time (date, month, year)
- Product (name, category)
- Customer (name, location)

## Example
A sales database:
- Fact Table: Sales
- Dimension Tables: Customer, Product, Time

## Advantages
- Simple and easy to understand
- Fast query performance
- Efficient for reporting and analytics

## Disadvantages
- Data redundancy
- Not ideal for complex relationships

## Conclusion
Star Schema is widely used in data warehousing for business intelligence due to its simplicity and performance.