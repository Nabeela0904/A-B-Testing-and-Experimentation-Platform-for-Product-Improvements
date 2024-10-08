# A-B-Testing-and-Experimentation-Platform-for-Product-Improvements
This project provides a platform for conducting A/B tests to evaluate product changes. It includes data preprocessing, hypothesis testing, and reporting functionalities to determine whether a product change improves performance over the control version.
The project focuses on conversion rate analysis, z-tests for proportions, and generating statistically significant insights.
The goal is to help businesses make data-driven decisions on product improvements based on the results of controlled experiments.
Features:
  Data Preprocessing: Clean and prepare data for analysis.
  Z-Test for Proportions: Perform statistical hypothesis testing to compare conversion rates between control and variant groups.
  Effect Size Calculation: Measure the strength of the effect between groups.
  Significance Testing: Calculate p-values to determine statistical significance.
  Insights and Recommendations: Generate a summary report with actionable insights based on A/B test results.
Technologies:
  Python: For data processing and statistical analysis.
  Pandas: For data manipulation.
  SciPy and Statsmodels: For hypothesis testing and statistical functions.
  Matplotlib/Seaborn: For visualizing the data. 
Dataset
The dataset contains user interaction data, including whether users were part of the control or variant group and whether they converted (e.g., made a purchase or took a desired action). The dataset has the following columns:

user_id: Unique identifier for each user.
group: Either 'ads' or 'psa'.
converted: Boolean indicating whether the user converted.
total ads: The number of ads seen by the user.
most ads day: Day of the week when the user saw the most ads.
most ads hour: Hour of the day when the user saw the most ads.  
Results:
  After running the A/B test, you will receive the following key insights:
  
  Conversion Rates: For both control and variant groups.
  P-Value: The probability of observing the results if the null hypothesis is true.
  Recommendation: Based on statistical significance, you will get a recommendation whether to implement the variant change or stick with the control version.  
  
  
