NYC Wi-Fi Hotspot Analysis
Project Overview
This project analyzes the distribution and accessibility of public Wi-Fi hotspots across New York City’s five boroughs. Using data from the NYC OpenData portal, the analysis examines the availability of free and limited free hotspots, their distribution relative to borough populations, and disparities in accessibility. The findings support recommendations for equitable Wi-Fi resource allocation.

Objectives:
Analyze the total number of hotspot locations across NYC, with a focus on free Wi-Fi availability.
Compare the number of hotspots in each borough relative to their population.
Identify borough-specific disparities and propose actionable recommendations for better internet accessibility.

Data Sources:
NYC Wi-Fi Hotspot Locations Dataset: Provided by NYC OpenData (https://data.cityofnewyork.us/City-Government/NYC-Wi-Fi-Hotspot-Locations/yjub-udmw/about_data).
Population Data: Sourced from (CityPopulation.de).

Tools and Technologies:
R Programming: For data cleaning, analysis, and visualization.
Leaflet: To create interactive maps showcasing Wi-Fi hotspot locations.
Excel: For initial data exploration and graphical summaries.

Key Analyses:
Univariate Analysis:

Assessed the distribution of hotspots by type (free, limited free, partner sites) and borough.
Calculated population-to-hotspot ratios to evaluate accessibility.

Bivariate Analysis:

Examined relationships between hotspot type and borough population to highlight disparities.

Spatial Visualization:

Created interactive maps using Leaflet to visualize hotspot locations and densities.

Results:
A total of 3,319 Wi-Fi hotspots were identified, with 2,736 free and 581 limited free locations.
Manhattan had the highest number of hotspots (1,672) and the best population-to-free-hotspot ratio (1,015:1). Staten Island had the least favorable ratio (10,223:1).
Disparities in hotspot distribution were not directly correlated with population size, suggesting borough-specific priorities drive allocation.
