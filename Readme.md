# Title
Exploratory Data Analysis of Credit Data

## Description
The project involves a consumer finance company, which is in the business of providing loans to consumers and earning from interest payments. An important goal of the company is to identify consumers who are likely to repay their loans and those that are likely to default in order to address two business risks:
(i) risk of business loss by rejecting consumers who are likely to repay loans, and
(ii) risk of financial loss by approving consumers who are likely to default.

The datasets from the company contain information regarding (i) applicant profiles and payment difficulties, and (ii) information about previous loans.

The goal of EDA is to identify the factors which indicate whether an applicant is likely to repay or default on a loan.

## Approach to Analysis
Analysis is done in 2 phases:
1. Inspection, cleaning and analysis of application_data.csv
2. Inspection and cleaning of previous_application.csv followed by merging with application_data.csv and subsequent analysis

The phases consist of the following steps:
1. Data Loading & Inspection
2. Data Cleaning
    2.1 Checking and ﬁxing header and footer rows
    2.2 Fixing missing values
    2.3 Removing duplicates
    2.4 Validating and standardising data
    2.5 Binning of continuous variables
3. Data Merging (in case of previous_application.csv only)
4. Data Analysis
    4.1 Analysis of Outliers
    4.2 Segmentation by the variable TARGET
    4.3 Univariate Analysis of Select Categorical Variables
    4.4 Univariate Analysis of Select Numeric Variables
    4.5 Bivariate & Multivariate Analysis
        4.5.1 Numeric - Numeric Analysis
        4.5.2 Numeric - Categorical Analysis
        4.5.3 Categorical - Categorical Analysis
    4.6 Correlations

## Insights
Insights drawn from the analysis are presented in the file Presentation.pdf