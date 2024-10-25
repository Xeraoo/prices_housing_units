# Prices of the housing units

## Overview

This project focuses on analyzing real estate unit prices across different regions of Poland, with a detailed examination of the property market in Kraków. The analysis includes both national and city-level insights, using various GIS tools to visualize spatial relationships and trends in the real estate market.

## Maps and Analysis

### 1. **Map of Average Unit Prices by County in Poland**
   - **Description**: A thematic map showing the average property unit prices across various counties (powiaty) in Poland.
   - **Purpose**: To provide a national overview of property prices and highlight regional variations in the real estate market.

![image](https://github.com/user-attachments/assets/6b83b7ec-7feb-4f53-af63-675bad773bfb)

### 2. **Price vs. Time Trend Chart**
   - **Description**: A graph illustrating the change in average unit prices over time.
   - **Purpose**: To show the temporal trend in property prices and how they have evolved in recent years.

![image](https://github.com/user-attachments/assets/49719965-e72d-4c35-8dc7-7807f87c16e0)

### 3. **Map of Property Transactions in Kraków (2019)**
   - **Description**: A map showing real estate transactions in Kraków for the year 2019, symbolized with graduated markers representing the transaction values.
   - **Purpose**: To visualize where the majority of property sales occurred and the price ranges in different parts of the city.

![image](https://github.com/user-attachments/assets/fd3e90f8-90ff-4444-8f18-10fdf3a2a1ea)
![image](https://github.com/user-attachments/assets/66fcf0e2-d956-486f-ae96-3df3729be8b9)

### 4. **Heatmap of Property Transactions in Kraków (2019)**
   - **Description**: A heatmap representing the density of property transactions across Kraków.
   - **Purpose**: To highlight hot spots in the property market where most transactions occurred.

![image](https://github.com/user-attachments/assets/22732a67-6d9c-49ad-85e8-87be3e8a5c02)

### 5. **Map of Average Property Prices by Subdistricts in Kraków**
   - **Description**: A thematic map displaying the average unit prices for properties in each subdistrict (obręb) of Kraków.
   - **Purpose**: To offer a detailed breakdown of property prices within different administrative boundaries of the city.

![image](https://github.com/user-attachments/assets/efb35bcc-da70-4433-ad7f-a3050ebaa78e)

### 6. **Map of Average Property Prices by Districts in Kraków**
   - **Description**: A map that visualizes the average property prices for different districts (dzielnice) in Kraków.
   - **Purpose**: To provide a higher-level view of property prices across the city's districts.

![image](https://github.com/user-attachments/assets/fd233b63-994a-4e26-b65a-5e465507c4ce)

### 7. **Spatial Interpolation of Prices (Kriging) for Kraków**
   - **Description**: A kriging interpolation map that estimates property prices across Kraków, based on available transaction data.
   - **Purpose**: To predict property price distribution for areas without direct transaction data, providing a continuous surface of estimated prices.

![image](https://github.com/user-attachments/assets/377903a3-59be-4d9c-bf54-c97252ed834e)

### 8. **Map of Distance to Public Transport Stops**
   - **Description**: A proximity analysis map showing the distance of properties to the nearest public transport stops in Kraków.
   - **Purpose**: To assess the accessibility of public transport from different properties, which can influence property values.

![image](https://github.com/user-attachments/assets/f7192c15-10cf-4acc-9200-8b6678711d7c)

### 9. **Isochron Map: Walking Time to Kraków City Center**
   - **Description**: An isochron map that shows areas categorized by walking time to the center of Kraków.
   - **Purpose**: To evaluate how location and accessibility to the city center impact property prices and desirability.

![image](https://github.com/user-attachments/assets/7cff2d65-2c48-4ef3-bd7b-8467810dea81)

## Tools and Software

- **QGIS**: All spatial data analysis and map creation were done using QGIS, a powerful open-source GIS software.
- **Data Sources**: Real estate transaction data, demographic information, and transport network data were used to conduct the analysis.

## Project Goals

This project aims to:
1. Provide insights into real estate market trends in Poland and Kraków.
2. Identify spatial patterns in property prices and transactions.
3. Explore the relationship between location, transport accessibility, and property prices.
4. Develop predictive models for property prices through spatial interpolation techniques.
