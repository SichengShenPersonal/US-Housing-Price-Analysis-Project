# Project Background



- **Phase 1: Python-Based Data Cleaning for Analytical Pipelines:**
This phase emphasizes data cleaning using Python to prepare a real-world housing dataset from the USA for downstream use by data analysts working with particularly dashboards. The cleaning process, powered by Pandas and NumPy, involves addressing missing values, normalizing data, and organizing the dataset for optimal analysis. Matplotlib is utilized for generating basic visualizations to explore key trends in the data. Statsmodels is employed to develop a regression model that assesses the relationship between factors such as internet coverage, population density, and housing prices, providing foundational insights that can be leveraged in the subsequent phases of the data pipeline.

- **Category 2:** 
- **Category 3:** 
- **Category 4:** 

The Jupyter Notebook used to clean and analysis data can be found here [link].

The interactive Tableau dashboards of determining factors in a state-level geograohical view can be found here [link].

The interactive Tableau dashboards of housing price overtime in a state-level geograohical vie can be found here [link].

# Determing factors analysis

- **Notice:** Most variables are statistically significant due to the large dataset. To determine important factors for housing price, R-squared is more useful.
- **Price vs Crime Rate:** A quadratic model shows a weak link between crime rate and housing prices (R-squared = 0.0165), indicating crime rate is not a crucial factor.
- **Price vs Population:** The log-log model indicates a positive relationship between population and housing price (R-squared = 0.3733), suggesting population might be important.
- **Price vs Population Density:** This model shows that 23.18% of price variation is explained by population density (R-squared = 0.2318), but other factors likely play a larger role.
- **Price vs Income:** The polynomial model indicates a strong link between income and housing price (R-squared = 0.5342), showing income is a key factor, with a non-linear impact as income rises.
- **Price vs Median Age:** The model shows a weak relationship (R-squared = 0.0212), suggesting median age has little effect on housing prices, despite statistical significance.
- **Price vs Unemployment:** This model suggests unemployment has minimal influence on housing prices (R-squared = 0.0031), even though the terms are statistically significant.
- **Price vs Race:** Race percentages (except Asian) have little effect on housing prices. However, the Asian percentage shows a significant impact (R-squared = 0.3921), suggesting it plays a notable role.
- **Price vs Education:** Higher education levels, especially college or above, are linked to higher housing prices (R-squared = 0.4734), while lower education levels are associated with lower prices.
- 
[Entity Relationship Diagram here]



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
