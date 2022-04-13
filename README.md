# KPMGDataQualityAssessment
Data Quality Assessment task provided by KPMG virtual internship

# 1. Data Quality Assessment
You are provided with the following dataset:
1. Customer Demographic 
2. Customer Addresses
3. Transactions data in the past 3 months

Task 1
Look at the datasets (Excel sheets with different tabs) provided by Sprocket Central Pty Ltd and identify all data quality issues.

Data Framework provided as an example:
Accuracy: Correct value
Completeness: Data Fields with values
Consistency: Values free from contradiction
Currency: values up to date
Relevancy: Data items with value Meta-Data
Validity: Data containing allowable values
Uniqueness: Records that are duplicated

My findings while assessing data
CustomerDemographics:
1. There are 126 Records with 'Last name' as Blank which is not a good practice
2. In gender column, expected values are only 2 - Female and Male. Some values have the wrong spelling and some values are present where Female is denoted by F and Male by M. The column needs to have one format values only, either Male/Female or M/F
3. DOB contains one record where the birth year is 1843 which is not possible. Also there are 89 records without a DOB i.e. it is blank
4. 500 records are missing their job titles
5. Agriculture in job_industry_category is misspelled
6. There is a column 'default' that has only junk characters and needs to be removed
7. 'Tenure' column has 88 records that are blank


Task 2
Create a PowerPoint presentation wihch outlines the approach we will be taking to identify which of the 1000 customers Sprocket Central Pty Ltd should target, based on this dataset. Explain the three phases:  Data Exploration; Model Development and Interpretation.

Task 3
Please develop a dashboard that displays your data summary and results of the analysis (see tools/references for assistance). Specifically, your presentation should specify who Sprocket Central Pty Ltd' should be targeting out of the new 1000 customer list. 
