---
title: "Air Quality"
date: 2020-05-01
author_profile: false
tags: 
 - R
 - times series
 - modeling
 - forecasting
 - visualizations
excerpt: "Social Distancing may be the solution for lower air pollution."
header:
  overlay_image: "/images/air.jpg"
  teaser: "/images/air.jpg"
  actions:
    - label: "Go to GitHub Repository"
      url: "https://github.com/jckett/Air_Quality"
---

# Time Series Forecasting of Air Quality in Los Angeles

# The Data

This project runs time series analysis on air quality data for Los Angeles between April 16, 2019 through April 30, 2020. Historical concentrations of NO2 and O3 were downloaded from [South Coast Air Quality Management District's database](https://xappprod.aqmd.gov/aqdetail/AirQuality/HistoricalData). Los Angeles COVID-19 case counts were retreived from [Los Angeles Times' GitHub repository](https://github.com/datadesk/california-coronavirus-data). 

## Technologies

This code for this project is split between Python, for data cleaning, and R, for data analysis. 

In Python, the following packages are used:
 - Pandas
 - datetime
 - Matplotlib
 
In R, the following packages are used:
 - readr
 - ggplot2
 - forecast
 - ffp2
 - TTR
 - dplyr
 - tidyr
 
# Launch

All necessary code for data cleaning is included in the Jupyter notebook, while all code for analysis is included in the R Markdown file. All data files can be found in the data folder. 
