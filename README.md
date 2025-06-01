# wildfire-simulation
Simulation for ECON136 - Wildfire Insurance
# Wildfire Simulation 🔥

This is a wildfire insurance simulation model built for **ECON136** at Stanford.

## Features
- Converts county acreage data into home-level risk exposure
- Assigns burn probability and property value to each home
- Allocates 10,000 homes across insurers based on:
  - Market share
  - Equalized expected loss
- Outputs detailed Excel files for analysis

## Files
- `allocation.py`: Core simulation logic
- `homes_data.xlsx`: Home-level risk + value + assignment
- `allocation_summary.xlsx`: Aggregated results by county/risk/insurer

## Run It
Make sure you have:

```bash
pip install pandas numpy openpyxl
python allocation.py
