Survey Data Duplicate Detection and Cleaning Using Python
Project Overview
___________________
This project focuses on detecting and removing duplicate records in a survey dataset.
The goal is to improve data quality before performing analysis.
The work simulates a real-world data analyst scenario where datasets often contain repeated or redundant records.
What the Project Does
Identifies duplicate and repeated rows in the dataset
Analyzes where duplicates occur and how they are distributed
Uses charts to study duplicates by country and employment type
Applies a strategic approach to remove duplicates
Keeps meaningful records and removes redundant ones
Deduplication Strategy
Instead of deleting only fully identical rows, a subset-based approach is used
Duplicates are identified using key profile columns:
MainBranch
Employment
RemoteWork
These fields represent the core identity of a respondent
This approach reflects realistic, business-driven data cleaning decisions
Workflow Steps
Load and explore the dataset
Detect duplicate records
Analyze duplicate patterns
Define uniqueness rules
Remove duplicates based on selected columns
Verify results after cleaning
Skills and Tools Used
Python
Pandas and NumPy
Data cleaning and preprocessing
Duplicate detection and deduplication logic
Matplotlib for visualization
Analytical reasoning and data quality validation
Outcome
The dataset becomes cleaner and more reliable
Only unique and meaningful records are retained
Duplicate and redundant entries are removed
The dataset is ready for further analysis or reporting
