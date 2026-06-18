# SCT_DS_4
# Traffic Accident Data Analysis

## Project Overview
This project analyzes traffic accident data to identify patterns related to **road conditions**, **weather**, and **time of day**. The goal is to uncover contributing factors to accidents and visualize **accident hotspots** to support data-driven road safety insights.

The analysis includes data cleaning, exploratory data analysis (EDA), and visualization techniques to highlight trends and risk factors associated with traffic accidents.

---

## Objectives
- Identify accident patterns based on:
  - Road conditions
  - Weather conditions
  - Time of day
- Visualize accident hotspots using spatial data
- Highlight key contributing factors to traffic accidents
- Provide insights that can support traffic safety improvements

---

## Dataset Description
The dataset contains records of traffic accidents with attributes such as:
- Accident location (latitude & longitude)
- Date and time of accident
- Weather conditions
- Road surface conditions
- Severity of accident
- Additional contributing factors (where available)

> **Note:** The dataset was preprocessed to handle missing values, inconsistent entries, and incorrect data types.

---

## Methodology

### 1. Data Cleaning & Preprocessing
- Removed or imputed missing values
- Standardized categorical variables (e.g., weather and road conditions)
- Converted date and time fields into usable formats
- Extracted time-based features such as:
  - Hour of day
  - Day vs night
  - Weekday vs weekend

---

### 2. Exploratory Data Analysis (EDA)
- Frequency analysis of accidents by:
  - Weather conditions
  - Road surface conditions
  - Time of day
- Comparative analysis of accident severity across conditions
- Trend analysis to identify peak accident periods

---

### 3. Visualization
The following visualizations were created:
- **Bar charts** showing accident counts by weather and road conditions
- **Time-of-day plots** highlighting peak accident hours
- **Heatmaps / Geospatial maps** to visualize accident hotspots
- **Correlation plots** to explore relationships between contributing factors

---

## Key Findings
- Accidents are more frequent during specific time windows (e.g., rush hours).
- Poor weather conditions (rain, fog, etc.) show higher accident involvement.
- Wet or damaged road surfaces contribute significantly to accident occurrence.
- Accident hotspots are concentrated in high-traffic urban areas and major intersections.

---

## Tools & Technologies Used
- Programming Language: Python
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Folium / GeoPandas (for hotspot mapping)
- Environment: Jupyter Notebook / Python Script

---

## Results & Insights
The analysis successfully identifies high-risk conditions and locations where traffic accidents are more likely to occur. These insights can help:
- Traffic authorities improve road infrastructure
- Policymakers design better safety regulations
- Urban planners optimize traffic flow and signage

---

## Conclusion
This project demonstrates how data analysis and visualization can be used to understand traffic accident patterns. By examining environmental and temporal factors, we gain actionable insights that 
