# Analyzing-Chronic-Disease-Indicators-in-the-United-States-Trends-Disparities-and-Insights
This project analyzes trends in chronic diseases across the United States using the CDC Chronic Disease Indicators (CDI) dataset. It investigates asthma, diabetes, cardiovascular disease, and alcohol-related mortality to highlight regional and demographic disparities and to inform public health policy decisions.

**Project Objectives**
Explore trends in asthma and diabetes mortality rates from 2019 to 2021.
Compare cardiovascular disease prevalence by gender and state.
Map geospatial patterns in alcohol-related mortality.
Provide an interactive Dash dashboard for real-time data exploration and actionable insights.

**Data Source**
The project uses the CDC Chronic Disease Indicators (CDI), which offers a comprehensive set of state-level data covering chronic diseases and associated risk factors. The CDI dataset is maintained by the Centers for Disease Control and Prevention (CDC) and aggregates public health surveillance data to support evidence-based decision-making. It includes 113 indicators across 21 topic areas, with stratifications by sex, race, ethnicity, and age where applicable. The dataset is public and is updated periodically to ensure relevance to guiding national and regional health policies.

https://data.cdc.gov/Chronic-Disease-Indicators/U-S-Chronic-Disease-Indicators/hksd-2xuw/about_data

**Methods and Approach**
Data Cleaning: Removal of empty columns, imputation of missing values using medians for numeric data, and "Unknown" placeholders for categorical.
Aggregation: Grouping data by year, state, and disease for focused analysis.
Trend Analysis: Using line plots to identify changes in asthma and diabetes mortality rates, noting a peak in 2020 linked to the COVID-19 pandemic.
Comparative Analysis: Gender-based comparison of cardiovascular disease prevalence across states.
Geospatial Visualization: Mapping alcohol-related mortality rates with Cartopy for clear regional insights.
Interactive Dashboard: Created with Dash to allow stakeholders to dynamically explore data by state and year, enhancing user engagement and understanding.

**Key Findings**
Mortality rates for asthma and diabetes peaked notably in 2020.
Cardiovascular disease shows higher prevalence among males, highlighting the need for gender-specific programs.
Southern and western states display higher alcohol-related mortality rates, signifying geographic health disparities.
States like California, Florida, and Texas require targeted public health interventions.

**Team Contributions**
Data collection, cleaning, geospatial analyses, dashboard design, trend analysis, and documentation were collaboratively undertaken by the project team.
