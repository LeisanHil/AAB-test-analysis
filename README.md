# AAB Test Analysis

Analysis of AAB testing in a large dating application.  
In addition to basic features, the app offers a premium subscription that provides access to several important additional features.  
An A/B test was conducted, wherein the price of the premium subscription for new users in several countries was adjusted when using two new payment systems. The cost of the trial period remained unchanged.  
**Objective**: Evaluate whether the experiment was successful overall.

### Tech Stack:

- **Pandas**, **NumPy**, **SciPy**, **Matplotlib**, **Seaborn**

### Project Implementation:

- Formulated null and alternative hypotheses from a business perspective.
- Conducted exploratory data analysis (EDA) and data preprocessing.
- Calculated and analyzed key product metrics (purchase conversion rate, ARPU, and ARPPU).
- Defined and stated statistical null and alternative hypotheses for each metric.
- Validated hypotheses using statistical tests in Python:
  - Chi-squared test
  - Bootstrap method
  - Shapiro-Wilk test for normality
  - Levene's test for homogeneity of variances

### Key Results:
> The changes implemented in the test group did not lead to statistically significant differences in purchase conversion rates, ARPPU, or ARPU compared to the control groups.
