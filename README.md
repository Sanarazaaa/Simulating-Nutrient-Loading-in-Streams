# USGS Water Data Plotter

This script fetches and visualizes **specific conductance** data from the USGS National Water Information System (NWIS) for a given site and date range.

##  What It Does

- Downloads **real-time water data** (parameter `00095`: Specific Conductance)  
- Resamples to **weekly averages**
- Plots the data using `matplotlib`

##  Parameters

- **Site:** `01491000`
- **Parameter:** `00095` (Specific Conductance)
- **Date range:** `2023-01-01` to `2023-06-01`

##  Requirements

```bash
pip install pandas requests matplotlib
