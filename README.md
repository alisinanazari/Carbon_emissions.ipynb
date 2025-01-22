# Carbon Emissions Analysis

## Overview
This repository contains a Jupyter Notebook file `Carbon_emissions.ipynb` that focuses on analyzing the relationship between carbon emissions and temperature trends over time. The notebook applies various statistical and machine learning techniques to gain insights into the underlying patterns and correlations within the data.

## Objectives
The main objectives of this project are:
1. **Exploring Data Trends:** 
   - Visualizing temperature (`temp_mean`) and carbon emissions (`carbon_mean`) trends across years.
2. **Correlation Analysis:** 
   - Calculating **Pearson** and **Spearman** correlation coefficients to evaluate the strength of relationships.
3. **Regression Analysis:** 
   - Using linear regression to model the relationship between year, temperature, and carbon emissions.
4. **Granger Causality Testing:** 
   - Determining whether carbon emissions have a causal relationship with temperature changes using the Granger Causality Test.
5. **Clustering:** 
   - Applying **K-Means clustering** to group periods with similar climate patterns.

## Methodology
The notebook covers the following steps:
1. **Data Preparation:**
   - Normalizing data for regression and clustering tasks.
   - Handling missing values (if any) and ensuring data quality.
2. **Exploratory Data Analysis (EDA):**
   - Plotting trends for temperature and carbon emissions across years.
3. **Statistical Analysis:**
   - Calculating correlation coefficients for identifying linear and rank-based relationships.
   - Conducting the Granger Causality Test to explore causal relationships.
4. **Machine Learning:**
   - Performing K-Means clustering to identify periods with distinct climate characteristics.
5. **Model Evaluation:**
   - Using R-squared (\( R^2 \)) scores to evaluate regression performance.

## Results
- **Correlation Analysis:** Strong/weak correlation between carbon emissions and temperature trends (based on Pearson and Spearman coefficients).
- **Regression Analysis:** Linear relationships between year, temperature, and carbon emissions with calculated slopes and intercepts.
- **Granger Causality Test:** p-values indicating causality for specific lag periods.
- **Clustering:** Identified clusters labeled as:
  - "High Temp & CO₂"
  - "Moderate Temp & CO₂"
  - "Low Temp & CO₂"

## Dependencies
The project uses the following Python libraries:
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `scikit-learn` for regression and clustering
- `scipy` and `statsmodels` for statistical analysis

