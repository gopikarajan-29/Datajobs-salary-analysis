# Data Science Jobs Salary Analysis
Comprehensive statistical and machine learning investigation of global pay trends for data science positions utilizing Python, EDA, time series forecasting, predictive modelling (Random Forest, XGBoost), and other tools. Using Seaborn, Plotly, and Power BI, findings were shown to reveal patterns across locations, employment types, and experience levels.

# Objectives
* Examine the disparity in pay between job titles, experience levels, firm size, and location.
* Conduct statistical hypothesis testing to assess how employment type, remote work, and other factors affect Salary.
* Create prediction models that use a variety of characteristics to estimate salary.
* Use time series models such as Prophet to forecast future patterns in salaries.
* For cross-country comparisons, normalize salaries using the Cost of Living Index (COLI) and Purchasing Power Parity (PPP).

# Methodology
 Methodology

1. Data Cleaning & Preprocessing
   - Handled nulls, removed duplicates, and standardized job titles.
   - Converted categorical codes (e.g., experience level) to descriptive labels.

2. Feature Engineering
   - Mapped job roles, experience, employment type, and remote ratios to new categories.
   - Created additional features like `region`, `salary_diff`, and normalized salary.

3. Exploratory Data Analysis (EDA)
   - Univariate, bivariate, and multivariate visualizations.
   - Heatmaps, boxplots, histograms, strip plots, and choropleth maps.

4. Statistical Analysis
   - Independent T-test for remote vs non-remote salaries.
   - ANOVA for employment type differences.
   - Chi-Square test for categorical associations (job title vs employment type).

5. Predictive Modeling
   - Regression models: Linear, Decision Tree, Random Forest, XGBoost, KNN.
   - Model evaluation using MAE, MSE, RMSE, and R² Score.

6. Time Series Forecasting
   - Used Prophet to predict salary trends from 2026 to 2030.

# Key Insights
  * The average salary for remote work is typically greater.
  * Compared to contract or freelance work, full-time jobs pay substantially more.
  * The best indicators of pay are job title and experience level.
  * There are differences in pay depending on the region and size of the company.
  * The accuracy of the predictive models was good (R2 > 0.8 in Random Forest/XGBoost).
