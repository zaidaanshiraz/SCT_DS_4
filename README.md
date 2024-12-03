# Traffic Accident Analysis (Skillcraft Technology Internship Project)

## Project Overview
This project analyzes traffic accidents in the United States based on data from [US Accidents Dataset](https://www.kaggle.com/datasets/sbhatti/us-accidents). The goal is to identify patterns in traffic accidents related to road conditions, weather, and time of day. Additionally, contributing factors such as the presence of traffic signals, stop signs, and junctions are also analyzed.

## Key Analysis
1. **Accidents by Road Condition**: Identifying how road conditions contribute to accidents.
2. **Accidents by Weather Condition**: Understanding the role of weather in traffic accidents.
3. **Accidents by Time of Day**: Analyzing the frequency of accidents by hour of the day and day of the week.
4. **Contributing Factors**: Examining other factors such as traffic signals, road type, and amenities.
5. **Geospatial Analysis**: Mapping accident locations to identify hotspots.

## Data Preprocessing
- Cleaned and formatted columns like `Start_Time`, `End_Time`, `Weather_Condition`, and `Road_Condition`.
- Extracted time-based features such as `Hour` and `Weekday`.
- Handled missing data for key columns.

## Visualizations
- Distribution of accidents based on road conditions, weather conditions, and time of day.
- Heatmaps and correlation matrices to identify relationships between contributing factors.

## Tools and Libraries
- Pandas for data manipulation
- Matplotlib and Seaborn for visualizations
- Geopandas for geospatial analysis
