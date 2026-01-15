# programming-for-data-science-coursework
Analysis of the NASA Carbon Monitoring System Carbon Flux Total L4 V3 (CMSFluxTotal) dataset for the Freeform Programming Exercise.

# Project Overview
A Python-based analysis project for the Programming for Data Science module, using NASA’s CMS-Flux Total Carbon Flux dataset (2010–2022) to explore global carbon flux trends, seasonal patterns, spatial variability, anomalies, and hemispheric differences through statistical and visual analysis.

# Dataset Source
Dataset Name: CMSFluxTotal201001_202212_v3.nc
Source: NASA Earthdata
Download from here: https://disc.gsfc.nasa.gov/datasets/CMSFluxTotal_3/summary
Access: Requires a free NASA Earthdata login

# Important note about the dataset
The dataset is NOT included in this GitHub repository due to file size limits (40+ MB). 
To run the notebook, download the dataset manually and place it in:
data/CMSFluxTotal201001_202212_v3.nc

# Instructions to run the code
1. Download the dataset from NASA Earthdata and place it inside the data/ folder.
2. Install required Python packages: pip install xarray numpy pandas matplotlib seaborn scipy netCDF4
3. Open the notebook (code.ipynb)
4. Run all cells in order

# Required Python Packages
1. xarray
2. numpy
3. pandas
4. matplotlib
5. seaborn
6. scipy
7. netCDF4

# Notebook Contents (code.ipynb)
A. Data Loading  
Loads the CMS-Flux dataset.
Converts variables into analysis‑ready formats.

B. Basic Analysis
1. Summary statistics
2. Global mean carbon flux trend
3. Seasonal cycle
4. Year‑to‑year variability
5. Histograms and scatter plots

C. Advanced Analysis
1. KDE distribution
2. Z‑score anomaly detection
3. Spatial map for selected month
4. Hemisphere comparison
5. Spatial hotspots
6. T‑test for hemispheric differences

D. Visualisations  
Multiple plots showing temporal and spatial behaviour of carbon flux.
