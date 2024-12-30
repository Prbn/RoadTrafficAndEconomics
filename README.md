# Road Traffic And Economics
GIS-based analysis exploring road traffic volume and its correlation with economic indicators like unemployment and population. Includes data preprocessing, spatial visualizations, and statistical models to uncover patterns and trends for urban planning and economic insights.

GIS Analysis of Traffic Volume and Economic Indicators

## Group Members:
- [Prabin Raj Shrestha](https://prbn.info/)
- [Arunava Das](https://www.linkedin.com/in/arunavadas005)
- [Heeyoon Shin](https://www.linkedin.com/in/heeyoon-shin-280480147/?trk=public_profile_samename-profile&originalSubdomain=sa)

## Project Overview:

This GIS project integrates traffic volume data with economic and demographic indicators to explore spatial patterns and correlations. By leveraging GIS methodologies, we aim to uncover insights into the relationship between transportation trends and economic activity.

## Objectives:
1.	Map and analyze spatial variations in traffic volume across regions and cities.
2.	Identify spatial correlations between traffic volume and economic indicators like GDP, employment rates, and consumer behavior.
3.	Conduct temporal-spatial analysis to detect trends, seasonal variations, and significant events.

## Table of Contents
1. [Introduction](#introduction)  
2. [Project Goals](#project-goals)  
3. [Datasets and GIS Layers](#datasets-and-gis-layers)  
4. [Tools and Libraries](#tools-and-libraries)  
5. [Research Questions](#research-questions)  
6. [Methodology](#methodology)  
7. [Results and Spatial Insights](#results-and-spatial-insights)  
8. [Usage Instructions](#usage-instructions)  
9. [Acknowledgments](#acknowledgments)  

## Introduction:

This GIS-based study explores traffic volume trends as a spatial and economic phenomenon. Using traffic data overlaid with economic and demographic indicators, we identify patterns that reflect regional economic dynamics and transportation behaviors.

## Project Goals:
	•	Collect, preprocess, and standardize traffic and economic data for GIS compatibility.
	•	Use GIS tools to visualize and analyze spatial patterns and temporal trends.
	•	Perform statistical and spatial correlation analyses to identify significant relationships.

## Datasets and GIS Layers:

## Datasets and GIS Layers:
- **Traffic Volume Data**:  
  - Portland, Oregon  
  - Virginia  
  - New York State
  Attributes: Traffic counts, road type, location coordinates, and temporal information.

- **Economic Indicators**:  
  - Market Hotness (FRED API)  
  - Unemployment Rates (FRED API)  
  - Annual Population (US Census)  
  - Subprime Credit Population (Equifax)
  Spatial Attributes: Regional boundaries, counties, states, and demographic information.

#### GIS Layers:
- Traffic Volume Heatmaps  
- Economic Indicator Choropleths  
- Combined Traffic-Economics Overlays  

## Tools and Libraries:
- GIS Tools:
- QGIS/ArcGIS: For mapping, geospatial analysis, and visualization.
- Google Earth Engine: For temporal GIS visualization and remote data access.
- Python Libraries:
  - pandas: Data preprocessing.
  - geopandas: Spatial data manipulation.
  - matplotlib: Spatial and temporal visualizations.
  - shapely: Geometric operations.
  - folium: Interactive mapping.
  - full-fred: Economic data integration from FRED.

## Research Questions:
1.	How does road traffic volume vary spatially across different regions and cities?
2.	Is there a spatial correlation between traffic volume and economic indicators?
3.	Are there significant temporal-spatial patterns or change points in traffic volume?

## Methodology
1. **Data Collection**: Sources include APIs, open data portals, and government agencies.  
2. **Data Processing**: Preprocessing for missing values, spatial alignment, and aggregation.  
3. **GIS Analysis**: Visualizations with heatmaps, overlays, and rolling averages.  
4. **Statistical Analysis**: Correlation and regression modeling. 

Results and Spatial Insights:

### Results and Spatial Insights

**Key Findings:**
1. **Traffic Volume Hotspots**:  
   - Hanover County, Virginia, exhibits the highest traffic volume.
   - Urban centers showed distinct patterns of higher traffic compared to rural regions. 
2. **Spatial Correlations**:  
   - Moderate negative correlation with unemployment rates.  
   - Weak positive correlation with population size and consumer behavior metrics.
3. **Temporal Trends**:  
   - COVID-19 caused a sharp decline in 2020 with region-specific recovery patterns.
   - Recovery patterns varied geographically, with urban centers rebounding faster. 


## Usage Instructions:

### Running the Analysis:
1.	Clone the repository:
  ```bash
  git clone https://github.com/Prbn/RoadTrafficAndEconomics
  ```

2.	Install required Python libraries:
   ```bash
   pip install pandas geopandas matplotlib folium full-fred
   ```

3.	Load GIS layers into your preferred GIS software (e.g., QGIS, ArcGIS).

4.	Run the Jupyter notebooks for analysis:
  - Traffic Volume Preprocessing
  - Spatial Analysis and Mapping
  - Temporal-Spatial Correlation

## View the interactive notebook on Google Colab:

Link to a copy of this notbook on colab: https://colab.research.google.com/drive/13s7vgERpROjoGXtSvKKzOo3eU8Yfo1sp

<a href="https://colab.research.google.com/drive/13s7vgERpROjoGXtSvKKzOo3eU8Yfo1sp" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Acknowledgments:
- We extend our gratitude to Syracuse University and our instructor for providing guidance and support. Special thanks to open data providers for making datasets accessible for analysis.
