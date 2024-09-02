# World Life Expectancy Summary

This project aims to analyze global life expectancy trends using a combination of data cleaning, SQL-based exploratory data analysis, and visualization through a Tableau dashboard. Below is a summary of the steps and methodologies used throughout the project:

1. Data Cleaning

The data cleaning process involved several key steps to ensure the accuracy and consistency of the dataset:
- Identifying and Removing Duplicates: Duplicate records were identified based on the combination of Country and Year columns.    Duplicate entries were removed to prevent data redundancy and maintain data integrity.
- Handling Missing Values in the Status Column: It was observed that some rows in the Status column were blank. Cross-referencing countries' statuses updated the dataset from existing records:
    - Countries previously marked as "Developing" were updated accordingly.
- Filling Missing Life Expectancy Values: The dataset contained a few missing values in the Life expectancy column.
  These missing values were imputed by averaging the life expectancy values from the preceding and following years for the same   country, ensuring the continuity and accuracy of life expectancy trends.
  
2. Exploratory Data Analysis (EDA)

Several SQL queries were used to explore the cleaned data and extract meaningful insights:
- Analyzing Life Expectancy Trends: The queries examined the minimum and maximum life expectancy values across different          countries to identify which countries had the most significant improvements over time.
- Average Life Expectancy Over Time: The project analyzed the average life expectancy across all countries for each year,         providing insights into global health trends over time.
- GDP and Life Expectancy Correlation: The relationship between GDP and life expectancy was explored to understand how economic   factors impact health outcomes.
- Comparison by Country Status: Life expectancy was compared between developed and developing countries to highlight the          differences in health outcomes based on socio-economic status.
- Adult Mortality Rate Analysis: The total adult mortality rates were calculated for each country over time, offering insights    into mortality trends and their impact on life expectancy.
  
3. Visualization with Tableau

A Tableau dashboard was created to visually present the analysis results, making it easier to interpret and communicate the findings. The dashboard includes the following key visualizations:
- Average Life Expectancy by Year: A line chart showing the trend of average life expectancy across all countries over the        years, highlighting global improvements or declines.
- GDP and Life Expectancy Correlation: A visualization illustrating the relationship between a country's GDP and its average      life expectancy, showing how wealth correlates with health outcomes.
- Comparison by Country Status: A bar chart comparing the life expectancy of developed versus developing countries, emphasizing   the disparities due to socioeconomic differences.
- Minimum and Maximum Life Expectancies Across Countries: A visualization showing the range of life expectancy (minimum and       maximum) for each country, allowing for a comparison of health disparities worldwide.
- Adult Mortality Rate Analysis: A chart displaying trends in adult mortality rates over time, highlighting changes and           providing insights into mortality factors.

Conclusion: 

This project showcases a comprehensive approach to analyzing and visualizing life expectancy data, leveraging SQL for data preparation and analysis and Tableau for effective data visualization. The insights gained from this analysis can inform public health strategies and policy decisions to improve global health outcomes.
