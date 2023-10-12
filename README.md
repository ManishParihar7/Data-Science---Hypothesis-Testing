# Data-Science---Hypothesis-Testing
# Statistical Analysis of Business Data

This repository contains Python code for conducting various statistical analyses on business data. The analyses cover several problem statements, each involving different statistical tests and inferences.

## Problem Statement 1: Cutlet Diameter Analysis

### Objective
To determine whether there is a significant difference in the diameter of cutlets between two units.

### Assumptions and Tests
- Assumption: The samples from both units are independent and normally distributed.
- Test: Two-sample t-test

### Inferences
- The calculated t-statistic is 0.72.
- At a 5% significance level, the p-value is less than 0.05.
- Conclusion: Reject the null hypothesis. There is a significant difference in the diameter of cutlets between Unit A and Unit B.

## Problem Statement 2: Laboratory Turn Around Time (TAT) Analysis

### Objective
To determine whether there is a difference in the average Turn Around Time (TAT) of laboratory reports among different laboratories.

### Assumptions and Tests
- Assumption: The samples from all laboratories are independent and normally distributed.
- Test: One-way ANOVA test

### Inferences
- The calculated p-value is less than 0.05.
- Conclusion: Reject the null hypothesis. There is a significant difference in average TAT among different laboratories.

## Problem Statement 3: Buyer Ratio Analysis

### Objective
To find out if the male-female buyer ratios are similar across different regions.

### Assumptions and Tests
- Assumption: The observed data is a contingency table of male and female buyers across regions.
- Test: Chi-squared test of independence

### Inferences
- The calculated p-value is less than 0.05.
- Conclusion: Reject the null hypothesis. Male and female buyer ratios are not similar across regions.

## Problem Statement 4: Defective Orders Analysis

### Objective
To check whether the defective percentage varies by processing center for customer order forms.

### Assumptions and Tests
- Assumption: The observed data is a contingency table of defective and non-defective order forms across processing centers.
- Test: Chi-squared test of independence

### Inferences
- The calculated p-value is less than 0.05.
- Conclusion: Reject the null hypothesis. The defective percentage varies by processing center.

## Getting Started

To run these analyses and conduct similar tests on your own data, you can follow these steps:

1. Clone this repository to your local machine.
2. Install Python and the required libraries (Pandas, NumPy, SciPy).
3. Use Jupyter Notebook or any Python IDE to open the provided code files.
4. Load your data or use the sample datasets provided in this repository.
5. Run the code for the specific analysis you're interested in.

## Acknowledgments

- These analyses are based on common statistical tests and practices in the field of data analysis.
- The sample datasets are provided for educational purposes.

Feel free to explore and use this code for your statistical analysis projects. If you have any questions or suggestions, please open an issue or reach out to the repository owner.

Happy analyzing!
