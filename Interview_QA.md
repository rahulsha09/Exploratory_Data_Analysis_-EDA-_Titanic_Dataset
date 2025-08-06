# EDA Interview Questions & Answers

**1. What is the purpose of EDA?**

EDA (Exploratory Data Analysis) aims to understand the main characteristics of a dataset using statistical summaries and visualizations. It helps in detecting errors, understanding patterns/trends, forming hypotheses, and preparing data for modeling.

**2. How do boxplots help in understanding a dataset?**

Boxplots visually summarize feature distributions, showing median, quartiles, and potential outliers. They allow quick comparisons of spread and central tendency across variables or groups, and highlight anomalies effectively.

**3. What is correlation and why is it useful?**

Correlation measures the linear relationship between two variables, usually ranging from -1 to 1. High correlation can indicate redundancy, help in feature selection, or expose potential dependencies that should be considered during modeling.

**4. How do you detect skewness in data?**

Skewness quantifies the asymmetry of a distribution. It can be calculated numerically, and visually checked with histograms or boxplots. Right-skewed means a long right tail, while left-skewed means a long left tail.

**5. What is multicollinearity?**

Multicollinearity occurs when two or more features are highly correlated with each other. This can cause problems in regression models by making coefficient estimates unstable and unreliable.

**6. What tools do you use for EDA?**

Common EDA tools include Pandas (data handling), matplotlib and seaborn (visualization), and occasionally plotly for interactive plots. Jupyter notebooks combine code, plots, and explanations for reproducibility.

**7. Can you explain a time when EDA helped you find a problem?**

While working on the Titanic dataset, EDA revealed that the `Age` column had many missing values and `Fare` was right-skewed with some large outliers. This guided feature engineering, e.g., imputing missing ages and scaling/transforming fares for models.

**8. What is the role of visualization in ML?**

Visualization makes summary statistics and data patterns tangible, enabling quick detection of trends, anomalies, or errors, and helping to communicate findings with stakeholders. It's crucial for both feature understanding and model diagnostics.
