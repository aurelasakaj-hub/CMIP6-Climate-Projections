# CMIP6 Climate Projections – SSP Scenario Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

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

---

## Data

- Source: [Pangeo CMIP6 Cloud Data](https://pangeo.io/)  
- Variables: **Temperature (tas)**, **Precipitation (pr)**  
- Scenarios: Historical, SSP2‑4.5, SSP5‑8.5  

---

## Tools

intake
intake-esm
xarray
pandas
numpy
matplotlib
scipy
jupyter 

---

## How to Run

1. Install required Python libraries (ideally in a virtual environment):  
   ```bash
   pip install xarray pandas numpy matplotlib scipy jupyter
   ```

2. Clone the repository:
   ```bash
   git clone https://github.com/aurelasakaj-hub/CMIP6-Climate-Projections.git
   cd CMIP6-Climate-Projections
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Author

**Aurela Sakaj**

- [LinkedIn](https://www.linkedin.com/in/auraela-sakaj)
- [GitHub](https://github.com/aurelasakaj-hub)
- [Email](mailto:sakaura3@gmail.com)

---

## Acknowledgements

This analysis uses CMIP6 data provided by the World Climate Research Programme's Working Group on Coupled Modelling. The Pangeo project is acknowledged for providing open access to cloud-hosted CMIP6 data.
