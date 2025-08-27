# Analyzing-Chronic-Disease-Indicators-in-the-United-States-Trends-Disparities-and-Insights
This project analyzes national and regional trends in chronic diseases across the United States using the CDC Chronic Disease Indicators dataset. It explores the prevalence and mortality rates of conditions such as diabetes, asthma, cardiovascular disease, and alcohol-related disorders, focusing on identifying significant health disparities and generating actionable public health recommendations.

Project Objectives
Examine trends in asthma and diabetes mortality rates (2019-2021).

Compare cardiovascular disease prevalence by gender and state.

Map geospatial patterns in alcohol-related mortality.

Empower public health stakeholders with insights for targeted interventions.

Data Source
CDC’s Centers for Disease Control and Prevention: Chronic Disease Indicators dataset

Contains over 309,000 records with 34 features on chronic disease metrics (state, year, gender, disease prevalence, mortality, and more).

Methods & Analysis
Data Cleaning: Dropped empty columns, filled missing values (median for numeric, “Unknown” for categorical fields).

Aggregations: Data grouped by year, state, and disease type to enable state-level and demographic analyses.

Trend Analysis: Identified yearly changes in diabetes and asthma mortality rates, highlighting anomalies during the COVID-19 pandemic.

Comparative Analysis: Assessed cardiovascular disease prevalence by gender across states, finding key gender disparities.

Geospatial Visualization: Used Cartopy to map alcohol-related mortality and identify regional hot spots.

Dashboard: Built with Dash, providing an interactive interface for exploring binge drinking prevalence trends by state and year.

Features
Advanced preprocessing for robust analysis.

Static visualizations (matplotlib) and interactive dashboards (Dash).

Code modularized for clarity: data loading, preprocessing, analysis modules, and visualization tools.

Actionable recommendations for policymakers based on statistical findings.

Key Results
Mortality rates for asthma and diabetes peaked in 2020, aligning with the COVID-19 pandemic.

Men are more affected by cardiovascular conditions than women.

States such as California, Florida, and Texas exhibit higher mortality and prevalence rates for multiple chronic diseases.

Regional disparities are evident in alcohol-related deaths, particularly in southern and western states.

Team Contributions
Data collection, cleaning, geospatial analyses, dashboard design, trend analysis, and documentation were collaboratively undertaken by the project team.
