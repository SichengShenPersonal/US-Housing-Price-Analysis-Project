# Project Background
This project aims to analyze housing prices across the United States using data collected from multiple sources at the county level. The dataset includes various aspects including housing prices, employment rates, median age, income, education levels, ethnic group, crime rate, population and population density. The goal is to understand how these factors influence housing prices across different states and observe housing price trends over time.

## Phase 1: Data Cleaning for Analytical Pipelines:

This phase emphasizes data cleaning using **Python** to prepare data for downstream use by data analysts, particularly those working with dashboards. The cleaning process, powered by **Pandas** and **NumPy**, addresses missing values, normalizes data, and organizes the dataset for optimal analysis. **Matplotlib** is used to generate basic visualizations to explore key trends in the data. **Statsmodels** is employed to develop a regression model that assesses the relationship between factors such as internet coverage, population density, and housing prices, providing foundational insights for subsequent phases of the data pipeline.

- The Jupyter Notebook used for data cleaning and analysis can be found here [link].

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


# Executive Summary

### Overview of Findings

Explain the overarching findings, trends, and themes in 2-3 sentences here. This section should address the question: "If a stakeholder were to take away 3 main insights from your project, what are the most important things they should know?" You can put yourself in the shoes of a specific stakeholder - for example, a marketing manager or finance director - to think creatively about this section.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
### Category 1:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 1]


### Category 2:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]


### Category 3:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


### Category 4:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
