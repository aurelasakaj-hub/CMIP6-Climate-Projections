# CMIP6 Climate Projections – SSP Scenario Analysis

This repository contains code and analysis for retrieving, processing, and analyzing 
climate model data from **CMIP6**. The focus is on **temperature and precipitation** 
changes under historical conditions and future Shared Socioeconomic Pathways (SSP2‑4.5 and SSP5‑8.5).

---

## Why This Matters

Understanding future climate trajectories under different emissions scenarios is essential for:
- Informing **energy transition policies**
- Preparing for **extreme weather events**
- Assessing **climate risks** to infrastructure and communities
- Supporting **evidence-based advocacy** on air quality and fossil fuels

This analysis provides the **quantitative foundation** for understanding how different 
socioeconomic pathways translate into measurable climate outcomes.

---

## Key Methods

| Method | Description |
|--------|-------------|
| **Multi-model ensemble averaging** | Combines outputs from multiple CMIP6 models to reduce uncertainty |
| **Statistical significance testing** | Validates whether scenario differences are meaningful |
| **Uncertainty quantification** | Visualizes ensemble spread to communicate confidence |
| **City-level data retrieval** | Extracts localized climate projections for specific urban areas |

---

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

- Python: `xarray`, `pandas`, `numpy`, `matplotlib`, `scipy`, `jupyter`  
- Jupyter Notebooks  

## How to Run

1. Install required Python libraries (ideally in a virtual environment):  
   ```bash
   pip install xarray pandas numpy matplotlib scipy jupyter
