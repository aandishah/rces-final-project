# rces-final-project

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pangeo-data/pangeo-docker-images.git/2022.09.21?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Faandishah%252Frces-final-project%26urlpath%3Dlab%252Ftree%252Frces-final-project%252FASamara_Final_Project.ipynb%26branch%3Dmain)

# Project Title:
Understanding ENSO drivers and responses to precipitation extremes on land using reanalysis data

# Research Questions: 
<ol>
    <li> How are the sea surface temperature and soil moisture anomalies [1979-2022] spatially correlated? Are they different spatially and quantitatively over land and over the ocean? </li>
   <li> Which years and regions show the largest impacts of the La Ninas and El Ninos? Are they similar or different? </li>
   <li> How well are these anomalies interpreted in ENSO teleconnections? </li>
</ol>

# Data

<ul> 
    <li> Sea Surface Temperature: 'http://iridl.ldeo.columbia.edu/SOURCES/.NOAA/.NCEP-NCAR/.CDAS-1/.MONTHLY/.Diagnostic/.surface/.temp/dods' </li>
    <li> Soil Moisture: https://github.com/google-research/ARCO-ERA5/blob/main/docs/0-Surface-Reanalysis-Walkthrough.ipynb -> 'gs://gcp-public-data-arco-era5/co/single-level-reanalysis.zarr' </li>
</ul>

# Methods 

As we enter yet another year of La Nina, it is important for us to understand how the long these large climatological impacts have on land. For my project, I will be calculating the SST and soil moisture anomalies from 1979 - 2022 on a seasonal scale (DJF, MAM, JJA, SON), and create threshhold to highlight the largest anomaly areas. Then I will be analyzing the spatial correlations between the SST and Soil Moisture. I will using the SciPy's Spatial algorithms and data structures to attempt to deconstruct the feedbacks that might be occuring due to ENSO.  