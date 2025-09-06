# NY-ATM-Analysis

## Overview
This repository contains a comprehensive analysis of ATM locations in New York State, based on the dataset `Bank-Owned_ATM_Locations_in_New_York_State.csv`. The analysis provides insights into the distribution of ATMs across cities and counties, competitive positioning of banks and credit unions, and opportunities for expansion. The code generates visualizations (bar charts, pie charts, and a heatmap) and a detailed report with strategic recommendations.

## Features
- **Data Cleaning**: Processes the dataset to handle missing values and extract geographic coordinates.
- **City Analysis**: Identifies the top 10 cities with the most ATMs and analyzes bank distribution in the top city.
- **County Analysis**: Highlights the top 10 counties and identifies low-density areas (<5 ATMs) for potential expansion.
- **New York City Analysis**: Examines ATM distribution across NYC counties (New York, Kings, Queens, Bronx, Richmond).
- **Institution Type Analysis**: Compares commercial banks vs. credit unions.
- **Visualizations**: Generates bar charts, pie charts, and a geographic heatmap.
- **Report**: Produces a detailed text report with strategic recommendations.

## Prerequisites
- Python 3.8+
- Required libraries:
  ```bash
  pip install pandas matplotlib seaborn geopandas folium
  ```
- Dataset: `Bank-Owned_ATM_Locations_in_New_York_State.csv` (place in the same directory as the script).

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Parham-Dehghan/NY-ATM-Analysis.git
   cd NY-ATM-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   python senior_financial_analyst_atm_report.py
   ```
4. Check the output files:
   - Charts: `top_10_cities_atm.png`, `top_10_counties_atm.png`, `top_10_banks_[city].png`, `nyc_atm_pie.png`, `nyc_atm_by_county.png`, `institution_type_pie.png`
   - Heatmap: `atm_heatmap.html`
   - Report: `atm_report.txt`

## Notes
- The dataset does not include transaction data (cash vs. card). Recommendations for collecting such data are included in the report.
- The code is modular, with separate functions for data cleaning, analysis, visualization, and reporting.
- Visualizations are saved as high-resolution PNG files (300 DPI) for professional presentations.

## Author
Senior Financial Analyst

## License
This project is licensed under the MIT License.
