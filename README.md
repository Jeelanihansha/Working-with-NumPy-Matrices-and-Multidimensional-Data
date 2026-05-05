# Working-with-NumPy-Matrices-and-Multidimensional-Data


Capstone Project 1: Analysis of NHANES Body Measurements
This project presents an analysis of adult male and female body measurement data using NumPy, Matplotlib, and statistical techniques. The dataset is based on National Health and Nutrition Examination Survey (NHANES) body measurements, and the work focuses on comparing distributions, calculating BMI, standardizing variables, and examining body proportion ratios.

Project Overview
The objective of this project is to explore multidimensional body measurement data and perform a comparative analysis of male and female participants. The notebook includes data loading, cleaning, visualization, descriptive statistics, BMI calculation, z-score standardization, correlation analysis, and ratio-based comparisons.

Tasks Covered
Load male and female NHANES body measurement datasets into NumPy matrices.
​

Clean missing values from the datasets before analysis.
​

Plot histograms and boxplots of male and female weights.
​

Compute descriptive statistics such as mean, median, standard deviation, minimum, and maximum.
​

Add BMI to the female dataset using weight and height.
​

Standardize the female dataset using z-scores.
​

Create scatterplot matrices and compute Pearson and Spearman correlations.
​

Calculate waist-to-height and waist-to-hip ratios for both groups.
​

Compare ratio distributions using boxplots.
​

Interpret the lowest and highest BMI observations using standardized measurements.
​

Technologies Used
Python

NumPy

Matplotlib

Pandas

Seaborn

SciPy

Google Colab / Jupyter Notebook

Dataset
The project uses NHANES anthropometric body measurement data published through CDC documentation and related NHANES data resources.
 The body measurement variables include weight, standing height, upper arm length, upper leg length, arm circumference, hip circumference, and waist circumference.
​

Key Analysis Areas
1. Weight Distribution Analysis
Weight distributions for male and female participants are explored using histograms and boxplots. These visualizations help compare central tendency, spread, and outliers between the two groups.
​

2. Descriptive Statistics
Basic numerical aggregates are computed to summarize the distributions of body weight. These include measures of location and dispersion such as mean, median, standard deviation, minimum, and maximum.
​

3. BMI and Standardization
Body Mass Index (BMI) is calculated for female participants using weight in kilograms divided by height in meters squared. Standardization is then applied to all female variables using z-scores so that the variables can be compared on a common scale.

4. Correlation Analysis
Relationships among height, weight, waist circumference, hip circumference, and BMI are explored using scatterplot matrices and correlation coefficients. Pearson and Spearman methods are used to study both linear and rank-based associations.
​

5. Ratio-Based Health Indicators
Waist-to-height ratio and waist-to-hip ratio are computed for both male and female participants. These measures help examine body fat distribution and central obesity patterns beyond BMI alon
