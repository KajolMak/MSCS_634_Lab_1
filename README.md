MSCS 634 Lab 1: Data Collection, Visualization, Preprocessing, and Statistical Analysis
Purpose
This lab demonstrates data exploration, visualization, preprocessing, and statistical analysis using Python and Jupyter Notebook. The goal is to prepare the dataset for deeper insights and to understand the relationships between variables.

Dataset
Name: sales_data.csv
Columns: Date, Advertising, Sales, Region
Source: [Your dataset source]
Key Insights
Total sales are highest in the West region.
Advertising spend correlates positively with sales.
Dataset is clean with no missing values.
Outliers were detected and removed using the IQR method.
Min-Max scaling was applied to numerical features for normalization.
Preprocessing Steps
Missing values: None in this dataset
Outlier detection and removal
Data reduction (column drop / sampling)
Data scaling using Min-Max normalization
Statistical Analysis
General overview using .info() and .describe()
Central tendency: Min, Max, Mean, Median, Mode
Dispersion: Range, Quartiles, IQR, Variance, Std Dev
Correlation analysis between numeric columns
Screenshots
All required screenshots are in the screenshots/ folder.

Challenges
Column name capitalization caused a KeyError initially.
Choosing appropriate outlier removal technique.
