# Mobility-Reduction-analysis
This project analyzes the impact of social distancing and mobility reduction policies during the COVID-19 crisis using aggregated mobility data. The analysis includes examining trends over time, identifying vulnerable areas, and clustering regions based on mobility reduction behavior.

# Table of Contents
Overview
Data
Analysis
Trend Analysis
Clustering Analysis
Vulnerability Analysis
Further Analysis
Contributing

# Overview
The government implemented social distancing and mobility reduction policies to curb the spread of COVID-19. This project uses mobility data collected over a week in 8-hour intervals to analyze the effectiveness of these policies.

# Data
The data files are named dayX_0000.csv, dayX_0800.csv, and dayX_1600.csv, where X represents the day (1 to 7). Each file contains the following columns:

Baseline: The number of people that used to move along this route before the crisis.
Crisis: The number of people that have been observed to move during the crisis.
x0, y0: The Longitude and Latitude centroids of the area of origin.
x1, y1: The Longitude and Latitude centroids of the area of destination.
index_0, index_1: Internal IDs.

# Analysis
Trend Analysis
Analyzes the overall trend in mobility reduction over time. Visualizes the reduction in mobility in 8-hour intervals over 7 days.

Clustering Analysis
Clusters areas into groups based on similar mobility reduction behavior using K-Means clustering.

Vulnerability Analysis
Identifies areas with the least reduction in mobility, highlighting potentially vulnerable regions.

# Further Analysis
Temporal Analysis: Analyze daily and time-of-day patterns in mobility reduction.
Demographic Analysis: Investigate the influence of population density and socioeconomic factors.
Policy Impact Analysis: Assess the impact of different policy measures.
Spatial Analysis: Examine the proximity to essential services and infrastructure.
Predictive Modeling: Develop models to forecast future mobility patterns.
# Contributing
Contributions are welcome!
