# Weight-Height-Outlier-detection-handling

## Introduction
This project demonstrates the process of detecting and handling outliers in the `weight` column. The objective is to ensure data quality and improve model performance by addressing extreme values that may distort analysis.

## Dataset Description
The dataset contains demographic and health-related information, including:
- `Weight`: Individuals' weights.

## Problem Statement
A boxplot revealed an outlier in the `weight` column, which exceeded the upper whisker based on the IQR method.

## Outlier Detection Methods
1. **Boxplot Visualization**: A visual inspection flagged one outlier.

## Approach to Handling Outliers
The following strategies were considered:
- **Capping**: The value was capped at the IQR threshold.
- **Retaining**: The outlier was left unchanged, as it did not significantly impact the overall dataset.

## Dataset
Get dataset from (here)[https://www.kaggle.com/datasets/mustafaali96/weight-height]
