# Exploratory_Data_Analysis_EDA_Titanic_Dataset

## Overview
In this repository we generate summary statistics, create histograms and boxplots for numeric features, use pairplot/correlation matrix for feature relationships, identify patterns, trends, or anomalies in the data and make basic feature-level inferences from visuals.

## Contents

- Full Python code with explanations.
- Answers to core EDA interview questions.
- Histograms, boxplots, a correlation matrix and heatmap for Titanic data.
- Full Colab-style markdown explanations for every EDA step.

## Main EDA Steps

1. **Summary Statistics**: Examine mean, median, std, etc., for numeric columns.
2. **Visualization**: Plot histograms and boxplots for key features (Age, SibSp, Parch, Fare).
3. **Relationships**: Analyze feature relationships with a correlation matrix and heatmap for clearity.
4. **Pattern Recognition**: Observe skews, anomalies, or any clear trends/patterns in the data.
5. **Feature-Level Inference**: Draw simple insights based on the analysis.


## Getting Started

- Import libraries pandas, seaborn and matplotlib.
- Place Titanic-Dataset.csv in the project folder.
- Write python code for EDA
- Generated images/plots/heatmaps for batter clearity and understanding.

## Detect Skew

**Skewness** measures if the data distribution has a long tail on one side.
If skew > 0.5, it's right-skewed (long tail right); if skew < -0.5, left-skewed; else it’s nearly symmetrical.
Skew tests the shape of the distribution, and high skew suggests possible need for transformation.

## Outlier Detection (IQR rule)

IQR is the range between 25th (Q1) and 75th (Q3) percentiles: IQR = Q3 - Q1
Outliers are values:
below Q1 - 1.5×IQR
IQR outlier detection helps flag data points much higher/lower than most others, useful for cleaning and quality control.
above Q3 + 1.5×IQR
---

