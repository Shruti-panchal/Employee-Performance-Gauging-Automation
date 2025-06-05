# Employee Performance Gauging Automation

## Overview
This Python-based automation extracts employee performance data from an Excel file, calculates key performance metrics, and visualizes insights to aid decision-making. The workflow includes data preprocessing, KPI calculation, and scorecard generation.

## Project Structure
-`performance_analysis.ipynb` - Core script for loading data, processing, calculating metrics, and generating visualizations.
- `requirements.txt` - List of dependencies for reproducibility.
- `Solution_Architecture.png` - High-level flow diagram illustrating data pipeline and processing.
- `Dummy_Data.xlsx` - Sample dataset used for performance scoring.
- `Final_Performance_Scorecard.xlsx` - Final Scorecard.
- `performance_analysis.ipynb` - Python Jupyter Notebook.
- `README.txt` - Documentation for running the solution.

## Installation
To install required dependencies, run:

"pip install -r requirements.txt"

Or, if using a Jupyter Notebook, execute each cell sequentially.

## Methodology

1. **Data Extraction:** Load `Dummy_Data.xlsx` and extract relevant sheets (`Data` & `Metrics Calculations`).
2. **Data Preprocessing:** Handle missing values, format dates, and clean inconsistencies.
3. **Metrics Calculation:** Compute individual employee report contributions and compare them with targets.
4. **Visualization:** 

Generate:
   - **Performance Breakdown** (Actual vs. Target comparison)
   - **Performance Score Distribution**
   - **Report Type Contribution (Pie chart)**
   - **Trendline (Reports over time)**


## Authors & Contact
- **Shruti** - Python Automation & Data Analysis
- [https://www.linkedin.com/in/shrutipanchal-/]
- [https://github.com/Shruti-panchal]

---
