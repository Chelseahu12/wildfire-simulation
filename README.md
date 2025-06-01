# wildfire-simulation
Simulation for ECON136 - Wildfire Insurance
# Wildfire Simulation

This is a wildfire insurance simulation model built for **ECON136** by Anya Dua, Chelsea Hu, and Maya Agarwal.

## Features
- Converts county-level data of acreage in 3 risk tiers into home-level risk exposure
- Assigns burn probability and property value to each home to compute expected loss
- Allocates 10,000 homes across insurers based on:
  a. Market share
  b. Equalized expected loss
- Outputs detailed Excel files for analysis

## Files
- `allocation.py`: Simulation code
- `homes_data.xlsx`: Home-level risk + value + assignment
- `allocation_summary.xlsx`: Aggregated results by county/risk/insurer

## Run It
Make sure you have:

```bash
pip install pandas numpy openpyxl
python allocation.py
