# CMIP6 Climate Projections – SSP Scenarios

This repository contains code and analysis for retrieving, processing, and analyzing 
climate model data from **CMIP6**. The focus is on **temperature and precipitation** 
changes under historical conditions and future Shared Socioeconomic Pathways (SSP2‑4.5 and SSP5‑8.5).

## Contents
- `Cmip6_city_data_retrieval.ipynb` – retrieves climate data (temperature & precipitation) for selected cities  
- `Climate_summary_analysis.ipynb` – statistical analysis of trends, deltas, and significance tests  
- `Models_ssp_timeseries.ipynb` – ensemble mean visualizations with uncertainty ranges  
- `Climate_Projections_CMIP6_SSP_Scenarios.pptx` – presentation summarizing results  

## Data
- Source: [Pangeo CMIP6 Cloud Data](https://pangeo.io/)  
- Variables: **Temperature (tas)**, **Precipitation (pr)**  
- Scenarios: Historical, SSP2‑4.5, SSP5‑8.5  

## Tools
- Python: `xarray`, `pandas`, `numpy`, `matplotlib`, `scipy`  
- Jupyter Notebooks  

## Author
Aurela Sakaj
