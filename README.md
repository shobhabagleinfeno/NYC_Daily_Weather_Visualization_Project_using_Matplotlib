# NYC_Daily_Weather_Visualization_Project_using_Matplotlib

Objective
The aim of this project is to analyze and visualize New York City's 2019 weather data. The analysis focuses on understanding temperature trends, precipitation, snowfall, and heating and cooling demands over the year.

Tools and Libraries
Python: The main programming language used.
Pandas: For data loading and manipulation.
Matplotlib: For creating visualizations.
KaggleHub: For accessing and downloading datasets directly from Kaggle.
Dataset
Source: National Weather Service (downloaded from Kaggle).
Columns:
date: Date in the format DD/MM/YYYY
tmax, tmin, tavg: Maximum, minimum, and average temperatures (°F)
departure: Difference from normal temperature (°F)
HDD and CDD: Heating Degree Days and Cooling Degree Days
precipitation, new_snow, snow_depth: Precipitation and snow measurements (inches)
Step 1: Data Loading and Preprocessing
Download and Load Data: The dataset was accessed and downloaded using the kagglehub library.
Data Exploration: pandas was used to inspect the first few rows and data types of each column to understand the structure and contents.
Date Formatting: The date column was converted to a DateTime format for easy manipulation and plotting over time.
Step 2: Visualization and Analysis
1. Temperature Trends
Purpose: To observe daily fluctuations in maximum, minimum, and average temperatures throughout the year.
Visualization: Line plot with separate lines for tmax, tmin, and tavg.
Insights: This plot provides a clear view of seasonal temperature changes and highlights the hottest and coldest periods of the year.
2. Precipitation and Snowfall Trends
Purpose: To analyze the variation in precipitation, new snowfall, and snow depth over time.
Visualization: Separate line plots for precipitation, new_snow, and snow_depth.
Insights: The plot reveals patterns in precipitation and snowfall, showing periods with heavy snowfall or rain.
3. Temperature Departure Distribution
Purpose: To examine how frequently daily temperatures deviated from the norm.
Visualization: Histogram and box plot of departure.
Insights: The histogram and box plot reveal the spread of temperature deviations, including any outliers.
4. Heating and Cooling Degree Days
Purpose: To assess heating and cooling demands across the year.
Visualization: Bar plot, with HDD and CDD displayed by month to show seasonal demand.
Insights: This plot shows that heating is needed more in winter, while cooling demand peaks in summer.
5. Precipitation vs. Average Temperature
Purpose: To explore any correlation between average temperature and precipitation.
Visualization: Scatter plot with tavg on the x-axis and precipitation on the y-axis.
Insights: The scatter plot shows if there’s any visible relationship between temperature and precipitation amounts.
6. New Snowfall Frequency
Purpose: To analyze snowfall frequency and amounts over the year.
Visualization: Histogram of new_snow values.
Insights: This plot shows the distribution of snowfall days and the frequency of significant snowfall.
7. Monthly Heating and Cooling Degree Days
Purpose: To visualize total heating and cooling degree days for each month.
Visualization: Stacked bar chart with HDD and CDD for each month.
Insights: This chart clearly depicts the seasonal energy demands for heating and cooling.
Conclusion
The analysis provides a comprehensive overview of New York City's weather in 2019. Key findings include:

Seasonal temperature trends with identifiable peaks and valleys.
Patterns of precipitation and snowfall, correlating to temperature.
Significant heating demands during winter months and cooling needs during summer.


Kaggle Dataset Link:  https://www.kaggle.com/datasets/alejopaullier/new-york-city-weather-data-2019/data
