# wildfire-allocation-simulation
Simulation for ECON136 - Wildfire Insurance
# Wildfire Simulation

This is a wildfire insurance simulation model built for **ECON136** by Anya Dua, Chelsea Hu, and Maya Agarwal.

## Features
- For each county, converts acreage in each risk tier into # homes in each risk tier
- Assigns burn probability (randomized from its risk tier) and property value to each home (randomized from mean property value in county)
- Allocates 10,000 homes across insurers based on:
  a. Market share: Each insurance company gets a number of homes proportional to their 2023 market share. 
  b. Equal expected loss: Each insurance company faces an equal expected loss from their contracts.
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
