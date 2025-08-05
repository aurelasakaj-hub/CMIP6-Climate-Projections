# CMIP6 Climate Projections – SSP Scenarios

This repository contains code and analysis for retrieving, processing, and analyzing 
climate model data from CMIP6. The focus is on temperature and precipitation 
changes under historical conditions and future Shared Socioeconomic Pathways (SSP2-4.5, SSP5-8.5).

## Contents
- `Cmip6_city_data_retrieval.ipynb` – extract climate data for selected cities  
- `Climate_summary_analysis.ipynb` – statistical analysis of trends and deltas  
- `Models_ssp_timeseries.ipynb` – visualizations of scenario time series  
- `Climate_Projections_CMIP6_SSP_Scenarios.pptx` – summary presentation  

## Data
- Source: [CMIP6 Climate Model Data](https://esgf-node.llnl.gov/search/cmip6/)  
- Variables: Temperature (tas), Precipitation (pr)  
- Scenarios: Historical, SSP2-4.5, SSP5-8.5  

## Tools
Python (xarray, pandas, numpy, matplotlib, scipy), Jupyter Notebooks
