# 🌍 World Bank Indicators Analysis using SQL

## 📌 Project Overview

This project focuses on exploring and analyzing World Bank economic indicators using SQL within a relational database environment. The main objective is to extract, filter, aggregate, and compare GDP-related data across countries and time periods.

## 🎯 Objectives

- Explore the database structure and understand table relationships
- Check data quality (missing values, row counts, distinct indicators)
- Analyze GDP per capita across different countries and years
- Compare economic performance between countries
- Use JOIN operations to combine multiple related tables

## 🗂 Database Tables Used

- **Country**: Contains country information
- **Indicators**: Contains economic measurements
- **Series**: Contains indicator metadata
- **CountryNotes**
- **SeriesNotes**
- **Footnotes**

The core analysis was mainly performed using:
- **Indicators** (economic measurements)
- **Country** (country information)
- **Series** (indicator metadata)

## 🛠 SQL Concepts Applied

- `SELECT`
- `WHERE`
- `ORDER BY`
- `GROUP BY`
- `COUNT()`
- `AVG()`
- `DISTINCT`
- `JOIN`
- Handling `NULL` values
- Subqueries (where needed)

## 📊 Key Analysis Performed

- Counted total rows and distinct indicators
- Checked for missing values
- Retrieved GDP per capita for Brazil
- Compared GDP per capita between Brazil and China
- Analyzed GDP data during the 1990s
- Identified the highest GDP per capita in 2014
- Compared average GDP per capita across countries
- Evaluated data availability (e.g., Angola case)
- Used `JOIN` operations to retrieve GDP-related data in 2014

## 💡 Key Insight

This project demonstrates how relational databases connect multiple tables using foreign keys and how SQL enables structured data exploration, aggregation, and comparative analysis to extract meaningful economic insights.

