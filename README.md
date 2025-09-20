# 🗂️ Data Science project 1: Practical Part

## Overview
This project demonstrates practical data engineering for country-level analytics using Python. Key tasks include web-crawling, CSV ingestion, rigorous dataset cleaning, feature engineering, and statistical analysis.

## Main Steps
### 1️⃣ Data Acquisition
- 🌐 Web-crawling demographics from Worldometers using `requests` and `BeautifulSoup`
- 📥 Importing GDP and population data from provided CSVs
- 🧾 Storing cleaned results in organized output files

### 2️⃣ Data Cleaning
- 🧹 Numeric conversion, type correction, missing value handling
- 🚫 Removal of invalid/outlier data using Tukey fences and log transformations
- 📛 Country name harmonization and duplicate handling

### 3️⃣ Feature Engineering
- 🏦 Calculating Total GDP via GDP per capita * Population
- 🔢 Applying log transforms to key features for normal distribution
- 📈 Feature scaling (z-score normalization) of core metrics

### 4️⃣ Data Integration & Output
- 🔗 Merging datasets with inner joins on standardized country names
- 🧮 Producing final NumPy feature matrix for downstream analysis
- 📊 Reporting cleaned tables, descriptive stats, and correlation analyses

## Skills Applied
- Python web-scraping & automation
- Data cleaning and wrangling with Pandas
- Outlier detection & statistical processing
- Feature transformation & scaling for ML
- Documentation and automated report generation

## Project Layout
ex1p_<ID>.zip/
├── code/
│   ├── demographics_crawler.py
│   └── other scripts
├── output/
│   ├── cleaned data & reports
│   ├── X.npy
│   └── summary files
└── consolidated_report.pdf
