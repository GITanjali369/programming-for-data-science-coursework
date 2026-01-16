# programming-for-data-science-coursework
Freeform Programming Exercise - Global Carbon Flux Analysis (2010–2022)

# Repository Contents
This repository contains my Programming for Data Science freeform exercise, where I analyse global carbon flux patterns using the NASA Carbon Monitoring System Carbon Flux Total L4 V3 (CMSFluxTotal) dataset. The project explores temporal, spatial, and statistical behaviour of carbon flux between 2010 and 2022.
1. code.ipynb - Full analysis notebook including data loading, cleaning, visualisations, and statistical analysis.
2. presentation.pptx — Final 10‑slide presentation summarising the dataset, visualisations, findings, and coding challenges.
3. README.md — Overview of the project and instructions for running the notebook.

# Project Overview
A Python-based analysis project for the Programming for Data Science module, using NASA’s CMS-Flux Total Carbon Flux dataset (2010–2022) to explore global carbon flux trends, seasonal patterns, spatial variability, anomalies, and hemispheric differences through statistical and visual analysis.

# Dataset Access
The CMSFluxTotal dataset is not included in this repository due to file size limits.
To run the notebook, download the dataset manually from NASA Earthdata.
After downloading, place the file in your working directory and update the file path in the notebook if necessary.

# Dataset Source
• Dataset Name: CMSFluxTotal201001_202212_v3.nc
• Source: NASA Earthdata
• Download from here: https://disc.gsfc.nasa.gov/datasets/CMSFluxTotal_3/summary
• Access: Requires a free NASA Earthdata login

# Important note about the dataset
The dataset is NOT included in this GitHub repository due to file size limits (40+ MB). 
To run the notebook, download the dataset manually and place it in:
data/CMSFluxTotal201001_202212_v3.nc

# How to Run the Notebook
1. Install required Python libraries: xarray, numpy, pandas, matplotlib, seaborn, scipy, netCDF4
2. Download the dataset from NASA Earthdata.
3. Update the dataset path in the notebook if needed.
4. Run all cells to reproduce the analysis and visualisations.

# Python Libraries
1. xarray
2. numpy
3. pandas
4. matplotlib
5. seaborn
6. scipy
7. netCDF4

# Summary of the Project
The analysis includes:
1. Summary statistics of carbon flux values
2. Global mean trend (2010–2022)
3. Seasonal cycle
4. Year‑to‑year variability
5. Histogram, KDE, and scatter plots
6. Spatial maps (June 2015 + hotspot map)
7. Hemisphere comparison and t‑test
8. Z‑score anomaly detection
9. Coding challenges and solutions.

All results are summarised in the accompanying PowerPoint presentation.

# References
1. NASA Goddard Earth Sciences Data and Information Services Center (GES DISC). Carbon Monitoring System (CMS) Carbon Flux Total L4 V3 (CMSFluxTotal); NASA Earthdata: Greenbelt, MD. DOI: 10.5067/ONM38W5QE1QI.
2. Hoyer, S.; Hamman, J. xarray: N‑D Labeled Arrays and Datasets in Python. J. Open Res. Softw. 2017, 5 (1), 1–6.
3. McKinney, W. Data Structures for Statistical Computing in Python. Proc. Python Sci. Conf. 2010, 51–56.
4. Hunter, J. D. Matplotlib: A 2D Graphics Environment. Comput. Sci. Eng. 2007, 9 (3), 90–95.
5. Virtanen, P.; et al. SciPy: Fundamental Algorithms for Scientific Computing in Python. Nat. Methods 2020, 17, 261–272.
6. Waskom, M. Seaborn: Statistical Data Visualization. J. Open Source Softw. 2021, 6 (60), 3021.
