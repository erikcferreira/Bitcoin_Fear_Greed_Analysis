# Bitcoin Price vs Fear & Greed Index

## Project Overview

This project analyzes the relationship between Bitcoin's historical price shifting and the "Crypto Fear & Greed Index." The goal is to identify if market sentiment correlates with price changes.

## Data Sources
- **Bitcoin Price:** Fetched via 'yfinance' (Yahoo Finance API).
- **Fear & Gread Index:** Fetched via Álternative.me' API.

- ## Methodology (ETL Pipeline)
1. **Extract:** Automated API calls to fetch raw data.
2. **Transform:**
   - UNIX timestamps conversion.
   - Data merging using Left Joins to preserve price history.
   - Handling missing values and data type casting.
3. **Load:** Exported clean data to CSV for visualization in Tableau.

## Technologies Used
- Python
- Pandas (Data Manipulation)
- Requests (API Connection)
- Yfinance
