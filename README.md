# Excel to Database Loader

A lightweight ETL tool that extracts tabular data from Excel (.xlsx), applies basic cleaning/validation, and loads it into a SQL database (MySQL or Postgres).

## Features
- Reads Excel sheets into a structured dataset
- Cleans column names (spaces -> underscores)
- Optional datetime parsing
- Loads into MySQL or Postgres
- Supports replace or append mode
- Simple CLI for repeatable imports

## Use cases
- One-off migration from Excel to a database
- Building a repeatable “ingestion” tool for dashboards
- Converting audit spreadsheets into structured data for analytics/ML

## Installation
```bash
pip install -e .
