# Project Overview
This project aims to analyze housing prices across the United States using data collected from multiple sources at the county level. The dataset includes various aspects including housing prices, employment rates, median age, income, education levels, ethnic group, crime rate, population and population density. The goal is to understand how these factors influence housing prices across different states and observe housing price trends over time.

## Phase 1: Data Cleaning for Analytical Pipelines:

This phase emphasizes data cleaning using **Python** to prepare data for downstream use by data analysts, particularly those working with dashboards. The cleaning process, powered by **Pandas** and **NumPy**, addresses missing values, normalizes data, and organizes the dataset for optimal analysis. **Matplotlib** is used to generate basic visualizations to explore key trends in the data. **Statsmodels** is employed to develop a regression model that assesses the relationship between factors such as internet coverage, population density, and housing prices, providing foundational insights for subsequent phases of the data pipeline.

- The Jupyter Notebook used for data cleaning and analysis can be found [here](https://github.com/SichengShenPersonal/us_housing_price_analysis_project/blob/main/Phase%201/Cleaning.ipynb).

## Phase 2: Visualization Key Housing Price Factors:

This phase focuses on the creation of an **interactive Tableau dashboard** that visually represents state-level data in a **geographical** format. The dashboard allows users to explore the relationships between housing prices and various factors such as population, income, crime rate, and education, presented through dynamic graphs for each state. This setup provides a deeper understanding of whether individual states have different preferences or key factors influencing housing prices, offering a clear comparison of how these relationships vary across the United States.

- The interactive Tableau dashboard showing determining factors in a state-level geographical view can be found [here](https://public.tableau.com/shared/J282T3PRR?:display_count=n&:origin=viz_share_link).

## Phase 3: Tableau Dashboard for State-Level Housing Prices Over Time:

In this phase, an **interactive Tableau dashboard** is designed to analyze housing price trends over time on a state-level basis. The dashboard displays a geographical view, allowing users to observe how housing prices have fluctuated across different states over the years. This **time-based analysis** helps identify long-term patterns, cyclical trends, and potential outliers in housing price movements, offering valuable insights into state-specific housing market dynamics and how they evolve over time.

- The interactive Tableau dashboard of housing prices over time in a state-level geographical view can be found here [link].

---
# Determing factors of Housing Price:
We used **R-squared** values from one-on-one regressions with housing prices to identify key factors. R-squared was chosen as the main indicator due to the large dataset, where statistical significance is less informative.

**Key Factors:** Population, population density, income, education, and Asian population percentage are important determinants of housing prices.

**Non-Key Factors:** Crime rate, median age, unemployment, and other race percentages show weak or minimal impact on housing prices.
