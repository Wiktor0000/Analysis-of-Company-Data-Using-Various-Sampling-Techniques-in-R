Data Analysis Project Using R

This project aims to utilize the R programming language for data analysis on a dataset containing information about companies from the "INC 5000 Companies" list from the year 2019. Various data sampling techniques are employed in the project, including cluster sampling, stratified sampling, and two-stage sampling, to obtain representative data samples and estimate different parameters, such as the average revenue of companies in various industries or the average revenue in different states.

Utilized Packages
The project makes use of several popular R packages, including:
readxl - for reading data from Excel files,
dplyr - for data manipulation,
janitor - for cleaning column names,
sampling and survey - for conducting various data sampling techniques,
stringr - for string manipulation.

The project defines the convert_revenue function, which converts revenue values from text form to numeric form, considering billion and million notations.

Stages of Data Analysis
Data Loading: The data is loaded from a CSV file, cleaned, only necessary columns are selected, and revenue values are converted.
Cluster Sampling: Random 10% of unique states are selected, and then all observations from those states are chosen for analysis.
Stratified Sampling: Data is stratified based on industries, and samples are drawn from each stratum.
Two-Stage Sampling: Initially, 3 states are randomly selected, and then all companies from those states are chosen for analysis.
Results Analysis: For each sampling technique, estimates of mean revenue values, estimation variances, and coefficients of variation are calculated.
