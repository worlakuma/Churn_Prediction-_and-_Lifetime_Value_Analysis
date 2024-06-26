# Machine Learning Prediction Model for a Telecommunications Provider
In the ever-evolving telecommunication sector, retaining customers and accurately forecasting churn are essential for sustaining growth and profitability. This project aims to harness advanced classification models to deliver comprehensive insights into customer dynamics for a prominent telecommunication company.

## Table of Contents
<!-- TOC-->

- [Step 1: Business Understanding](#step-1-business-understanding)
  - [Scenario](#scenario)
  - [Objective](#objective)
  - [Hypothesis: ...](#hypothesis-)
  - [Key Business Questions](#key-business-questions)
  - [Approach](#approach)
- [Step 2: Data Understanding](#step-2-data-understanding)
  - [Project Initialisation](#project-initialisation)
  - [Data Collection](#data-collection)
    - [Access the LP2_Telco_churn_first_3000 data from Microsoft SQL Server](#access-the-LP2_Telco_churn_first_3000-data-from-microsoft-sql-server)
      - [Connect to the database using provided credentials](#connect-to-the-database-using-provided-credentials)
      - [Fetch Information Schema for tables in the database](#fetch-information-schema-for-tables-in-the-database)
    - [Load LP2\_Telco\_churn\_first\_3000 Data](#load-lp2_Telco_churn_3000-data)
    - [Access the LP2_Telco_churn_second_2000 data from GitHub Repository](#access-the-LP2_Telco_churn_second_2000-data-from-github-repository)
    - [Access the Telco-churn-last-2000 data from OneDrive](#access-Telco-churn-last-2000-data-from-onedrive)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
- [Step 3: Data Preparation](#step-3-data-preparation)
  - [Split data set into X, y](#Split data set into X, y)
  - [Split data set into training and evaluation]
  - [Feature Engineering (Creating New Features, (binning & bucketing), Handling Missing Data, Encoding, Standardization, 
        Normalization, Scaling)]
    - [Create a pipeline to preprocess the data]
      - [Separate inpute features into numeric and categorical for different pipelines]
      - [Handle missing values using imputation Techniques]
      - [Scaling or normalize numeric features]
      - [Encode categorical features]
      - [Transformations for skewed data (log, power, custom, etc)]
      - [Balance dataset (depending on what you see)]

<!-- /TOC -->

## Worlflow
![A beautiful sunset](https://example.com/sunset.jpg "Sunset at the beach")



  
 
