# Correlation Analysis Project: Movies Gross vs. Budget and Companies

## Project Overview

This project involves analyzing the correlation between movies' gross revenue and budget, along with exploring the relationship between different companies and these financial metrics. The goal is to uncover insights into how movie budgets correlate with gross revenue and if there are notable differences among companies.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Analysis](#analysis)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [Dependencies](#dependencies)
8. [Usage](#usage)
9. [License](#license)

## Introduction

This project aims to perform a detailed correlation analysis to understand:
- The relationship between movie budgets and their gross revenue.
- How these relationships differ across various movie production companies.

## Dataset

The dataset used in this project includes information about movies, including their budget, gross revenue, and production companies. The data is sourced from [Insert source if applicable] and is provided in a CSV file format.

**File:** `movies.csv`

### Dataset Columns
- `Movie`: Name of the movie
- `Budget`: Budget of the movie (in USD)
- `Gross`: Gross revenue of the movie (in USD)
- `Company`: Production company of the movie

## Methodology

1. **Data Loading**: Load the dataset using pandas.
2. **Data Cleaning**: Handle missing values, incorrect data types, and remove any anomalies.
3. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics for budget and gross revenue.
   - Distribution plots and scatter plots to visualize relationships.
4. **Correlation Analysis**:
   - Compute Pearson, Kendall, and Spearman correlation coefficients.
   - Visualize correlations using heatmaps.
5. **Company-wise Analysis**:
   - Compare correlations and financial metrics across different companies.
   - Analyze if certain companies have better financial returns relative to their budget.

## Analysis

The analysis is divided into the following sections:

1. **Budget vs. Gross Revenue**:
   - **Scatter Plot**: Visualize the relationship between budget and gross revenue.
   - **Correlation Coefficients**: Calculate Pearson, Kendall, and Spearman correlations.

2. **Company-wise Analysis**:
   - **Group Analysis**: Analyze budget and gross revenue for different companies.
   - **Correlation by Company**: Determine if there are significant differences in correlations across companies.

## Results

- **Budget vs. Gross Revenue**:
  - The Pearson correlation coefficient is [X].
  - The Kendall correlation coefficient is [Y].
  - The Spearman correlation coefficient is [Z].
  - Interpretation of the results.

- **Company-wise Analysis**:
  - Summary of insights on how different companies perform.
  - Notable differences in budget efficiency among companies.

## Conclusion

The analysis provides insights into the financial relationships in the movie industry. Key findings include [Summarize key findings]. This can help stakeholders make informed decisions about movie production and budgeting strategies.

## Dependencies

The following Python libraries are required for this project:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`


