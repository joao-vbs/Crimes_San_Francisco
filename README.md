San Francisco Crime Data Analysis
This repository contains an exploratory data analysis (EDA) of crime data from San Francisco. The analysis focuses on uncovering patterns and insights related to the occurrence of crimes across various districts, time periods, and specific locations within the city.

Table of Contents
Introduction
Dataset
Objectives
Analysis Summary
Key Findings
Conclusion
How to Run
Dependencies
Introduction
The purpose of this project is to explore and analyze crime data from San Francisco to identify trends, patterns, and hotspots. The analysis helps in understanding the distribution of different crime categories, the impact of time and location on crime occurrences, and potential areas where law enforcement efforts could be focused.

Dataset
The dataset used in this analysis includes records of crimes reported in San Francisco. Key features of the dataset include:

IncidntNum: Unique identifier for each crime incident.
Category: The type of crime (e.g., Larceny/Theft, Assault).
Date: The date the crime was reported.
PdDistrict: The police district where the crime occurred.
Address: The address where the crime took place.
X, Y: The geographical coordinates of the crime location.
Objectives
The main objectives of this analysis are:

To understand the distribution of crimes across different police districts.
To analyze the temporal patterns of crime occurrences (by month and time of day).
To identify specific addresses with high concentrations of crime.
To provide actionable insights for law enforcement and public safety strategies.
Analysis Summary
The analysis is divided into several sections:

Crime Distribution by Category: Examination of the most common types of crimes in San Francisco.
Geographical Analysis: Exploration of crime distribution across different police districts and specific addresses.
Temporal Analysis: Analysis of how crime rates change over time, focusing on monthly trends.
Top Addresses for Crime: Identification of the addresses with the highest number of reported crimes.
Key Findings
The Southern District has the highest crime rate, followed by the Northern and Mission districts.
Certain addresses, particularly on Bryant St and Market St, are significant hotspots for criminal activity.
Crime rates are relatively stable throughout the year, with a slight increase in October.
Conclusion
The findings from this analysis suggest that crime prevention efforts should be focused on high-crime districts and specific hotspots, such as major thoroughfares and commercial areas. Consistent enforcement and community engagement are key to reducing crime rates in these areas.

How to Run
To run the notebook locally:

Clone the repository: git clone https://github.com/your-username/your-repository-name.git
Navigate to the repository directory: cd your-repository-name
Open the notebook in Jupyter: jupyter notebook crime_analysis.ipynb
Dependencies
The notebook requires the following Python libraries:

pandas
numpy
matplotlib
seaborn
folium
wordcloud
