# Task 1: Big Data Analysis

## Dataset
- Source: Kaggle
- Format: CSV (converted from Excel)
- Rows: 1,004,480
- Columns: Date, Domain, Location, Value, Transaction_count

## Tools Used
- Python
- Pandas (initial analysis)
- Dask (scalable analysis)

## Analysis Performed
- Grouped by Domain to find total transaction value and count
- Identified top 10 locations by transaction value
- Analyzed monthly transaction value trends

## Key Insights
- **Top Domain**: PUBLIC (₹107.79B)
- **Top Location**: Bhopal (₹16.55B)
- **Peak Month**: August 2022 (₹64.09B)

## Deliverables
- `analysis.py`: Pandas-based script
- `dask_analysis.py`: Scalable Dask-based script
- `README.md`: Summary of project and insights