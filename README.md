# Analyzing International Debt Statistics

![US Dollar](image.jpg)

## Overview

An analysis of international debt data collected by The World Bank, exploring debt owed by developing countries across various categories. This project uses SQL to query a PostgreSQL database containing debt indicators for 124 countries.

## Data

The analysis uses the `international_debt` table from The World Bank:

| Column | Description | Data Type |
|--------|-------------|-----------|
| country_name | Name of the country | varchar |
| country_code | Code representing the country | varchar |
| indicator_name | Description of the debt indicator | varchar |
| indicator_code | Code representing the debt indicator | varchar |
| debt | Value of the debt indicator in current US dollars | float |

## Key Findings

**124 distinct countries** are represented in the database.

**China holds the highest total debt** at approximately $285.8 billion USD across all debt indicators.

**Timor-Leste has the lowest principal repayments** on external long-term debt at $825,000 USD.

## Tools

- PostgreSQL
- Jupyter Notebook

---

*This was a pre-setup project by DataCamp. The work was mine, but the plan was theirs.*