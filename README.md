# README
## Homework 8 - World Bank Analysis
### Author

- Name: Jae Skeete

- Email: skeetej@vcu.edu

- GitHub: cmsc408-sp2025-hw8-skeetej

This project analyzes World Bank economic and demographic data using SQL. It explores country classifications, regional income distributions, and data validation tasks.

### Features

20 SQL Tasks: From basic counts to advanced pivoting and percentage calculations.

- Data Cleaning: Filters non-country entries and corrects data inconsistencies.

- Dynamic Reporting: Uses CASE statements and CTEs to generate pivot tables.

### Prerequisites
- Python 3.8+

- MySQL Server

- Libraries: python-dotenv, mysql-connector-python

### Installation
Clone the repository:

```bash
git clone https://github.com/cmsc-vcu/cmsc408-sp2025-hw8-skeetej.git
```
Install dependencies:

```bash
poetry install
```
Configure MySQL:

Create a .env file with your MySQL credentials:

```text
CMSC408_HW8_USER=your_username
CMSC408_HW8_PASSWORD=your_password
CMSC408_HW8_HOST=localhost
CMSC408_HW8_DB_NAME=world_bank_data
```
Usage

- run: poetry shell. cd to reports, run quarto render report.qmd

Key Tasks:

Task 5: Count countries with 2020 data.

Task 15: Pivot table of income groups by region.

Task 18: Identify missing region-income group pairs.

### Acknowledgments:

Data sourced from the World Bank's World Development Indicators.

