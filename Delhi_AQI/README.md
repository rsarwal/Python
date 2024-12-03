# Delhi Air Quality Index (AQI) Analysis

This project focuses on analyzing the air quality in Delhi, India, using various air quality parameters. The data includes air quality measurements from multiple sensors, with the goal of assessing the air quality levels over time and offering insights into the air pollution situation in Delhi.

## Project Overview

Delhi, one of the most polluted cities in the world, faces critical air quality issues that directly impact its citizens' health. This project aims to analyze and visualize the **Air Quality Index (AQI)** for different locations across Delhi over a specified period, using data from **CPCB's public data repository**.

The analysis is performed using Python and involves data preprocessing, exploratory data analysis (EDA), statistical analysis, and visualization.

### Data Files:
- **AirQualityIndex.ipynb**: Jupyter notebook containing the Python code for data analysis.
- **aqi_data.csv**: Raw data containing AQI readings from multiple sensors.
- **cleaned_aqi_data.csv**: Cleaned and preprocessed version of the raw AQI data.
- **Additional CSV Files**: Data files representing AQI readings from different locations in Delhi.

## Methodology

1. **Data Collection**:
   - The raw data comes from air quality sensors located in different parts of Delhi. It includes parameters like AQI, PM2.5, PM10, CO2, NO2, and other pollutants.
   
2. **Data Preprocessing**:
   - The data is cleaned to handle missing values, normalize units, and handle any inconsistencies.
   - Outliers are detected and handled to ensure accurate analysis.

3. **Exploratory Data Analysis (EDA)**:
   - Key statistical metrics such as the mean, median, and standard deviation are calculated to understand the air quality trends.
   - Visualizations are created to observe the distribution of pollutants, seasonal trends, and comparisons across different areas.

4. **Analysis**:
   - AQI trends over time are analyzed to identify peak pollution periods.
   - The relationship between various pollutants (PM2.5, PM10, NO2, etc.) and AQI is explored.
   - Pollution levels across different locations in Delhi are compared to identify the most affected areas.

5. **Visualization**:
   - Various plots such as line plots, bar charts, and heatmaps are used to visualize the AQI trends over time and across different regions.
   - The analysis includes visualizations like:
     - AQI distribution over time
     - Comparison of AQI levels between locations
     - Correlation heatmap of different pollutants

## Key Insights

- **High Pollution Areas**: Certain locations in Delhi consistently report higher AQI levels, often exceeding the safe limit.
- **Pollution Peaks**: The AQI levels are highest during the winter months, particularly due to factors like crop burning in nearby areas and lower wind speeds.
- **Pollutants Correlation**: PM2.5 and PM10 levels are strongly correlated with the AQI, indicating their significant contribution to air quality deterioration.

## Visualizations

The project includes several key visualizations to highlight the findings:

- **AQI Distribution Over Time**: Line plot showing the trend of AQI over the months.
- **Pollution Levels by Location**: Bar chart comparing AQI values across different areas in Delhi.
- **Pollutant Correlation**: Heatmap visualizing the relationships between different pollutants (PM2.5, PM10, NO2, etc.) and AQI.


---

**Data Source**  Air Quality data was sourced from the CPCB's public data repository.

https://airquality.cpcb.gov.in/ccr/#/caaqm-dashboard-all/caaqm-landing/caaqm-data-repository
