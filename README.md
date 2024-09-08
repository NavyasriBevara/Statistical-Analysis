# Statistical-Analysis

# Summary:
The document provides an overview of statistical analysis techniques in Python, using a dataset related to health metrics. Here's a summary:

Data Import and Overview:

The dataset is read using Pandas, containing columns like AGE, SEX, BMI, STUDENTS, SMOKING, and FINE.
Initial exploration includes displaying the first few rows, calculating basic statistics (mean, median, mode), and variance.
Descriptive Statistics:

Calculations include the variance, standard deviation, kurtosis, skewness, and range for each column.
Example: The mean BMI is calculated, along with its standard deviation, skewness, and kurtosis.
Inferential Statistics:

A T-test is performed to compare the BMI against a population mean of 0.03. The results show a significant difference with a T-Statistic of 183.75 and a P-Value of 0.0.
A 95% confidence interval for BMI is calculated, showing a range of approximately 30.34 to 30.99.
Regression Analysis:

A linear regression model is fitted to predict FINE based on BMI.
The model summary includes an R-squared value of 0.039, indicating a weak relationship between BMI and FINE.
The regression coefficient for BMI is 393.87, with a P-value of 0.000, suggesting a statistically significant relationship.
The document provides a step-by-step analysis, from basic descriptive statistics to more complex inferential statistics and regression analysis, using Python libraries like Pandas, NumPy, SciPy, and Statsmodels.







