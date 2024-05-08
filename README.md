# Boston Housing Market Analysis
### Overview
This project provides a comprehensive analysis of the Boston Housing dataset. 

### Dataset Description
The Boston Housing dataset contains the following variables:

**CRIM:** Per capita crime rate by town.  
**ZN:** Proportion of residential land zoned for lots over 25,000 sq.ft.  
**INDUS:** Proportion of non-retail business acres per town.  
**CHAS:** Charles River dummy variable (1 if tract bounds river; 0 otherwise).  
**NOX:** Nitric oxides concentration (parts per 10 million).  
**RM:** Average number of rooms per dwelling.  
**AGE:** Proportion of owner-occupied units built prior to 1940.  
**DIS:** Weighted distances to five Boston employment centres.  
**RAD:** Index of accessibility to radial highways.  
**TAX:** Full-value property-tax rate per $10,000.  
**PTRATIO:** Pupil-teacher ratio by town.  
**LSTAT:** Percentage lower status of the population.  
**MEDV:** Median value of owner-occupied homes in $1000's.

### Objectives
The analysis focuses on several key questions about the Boston housing market:

1. Is there a significant difference in the median value of houses bounded by the Charles river or not?
2. Is there a difference in median values of houses of each proportion of owner-occupied units built before 1940?
3. Can we conclude that there is no relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town?
4. What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner-occupied homes?

### Tasks and Analysis
#### Descriptive Statistics and Visualizations
- Boxplot for MEDV
- Bar Plot for CHAS
- Boxplot for MEDV vs. AGE
- Scatter Plot for NOX vs. INDUS
- Histogram for PTRATIO

### Hypothesis Testing
- T-test: Checks if there's a significant difference in the median value of homes by the river.
- ANOVA: Analyzes differences in home values across various ages of properties.
- Pearson Correlation: Tests the relationship between nitric oxide concentrations and non-retail business acres.
- Regression Analysis: Determines the impact of distance to employment centers on home values.

**Conclusions:**
For each hypothesis tested, conclusions are drawn based on the p-values and statistical significance, adhering to an alpha level of 0.05.

### Repository Structure
- data/: Contains the dataset used in the analyses.
- notebooks/: Jupyter notebooks documenting the analyses and findings.
- scripts/: Python scripts for custom analysis functions.
- output/: Graphs and result summaries generated from the analyses.

### How to Use:
1-Clone the repository.
2-Install required dependencies.
3-Run the Jupyter notebooks to view the analysis.

### Dependencies:
-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-SciPy
-Statsmodels
