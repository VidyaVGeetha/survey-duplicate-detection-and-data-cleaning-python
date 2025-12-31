📊 Survey Data Duplicate Detection and Cleaning Using Python
🧾 Project Overview
This project focuses on detecting and removing duplicate records in a survey dataset to improve data quality before performing analysis. It simulates a real-world data analyst scenario where datasets often contain repeated, inconsistent, or redundant records.
✅ What the Project Does
Detects duplicate and repeated rows in the dataset
Analyzes where duplicates occur and how they are distributed
Visualizes duplicates by Country and Employment Type
Applies a strategic approach to remove duplicates
Retains meaningful records and removes redundant ones
🧠 Deduplication Strategy
Instead of deleting only fully identical rows, the project uses a subset-based uniqueness approach.
Duplicates are identified using key profile columns:
MainBranch
Employment
RemoteWork
These columns represent the core identity of a respondent and reflect realistic, business-driven data-cleaning logic.
🔧 Workflow Steps
Load and explore the dataset
Detect duplicate records
Analyze duplicate patterns
Define uniqueness rules
Remove duplicates using selected key columns
Verify dataset after cleaning
🛠️ Skills / Tools Used
Python
Pandas & NumPy
Data Cleaning and Pre-processing
Duplicate Detection & Deduplication Logic
Matplotlib Data Visualization
Analytical Reasoning & Data Quality Validation
🎯 Outcome
Cleaner and more reliable dataset
Duplicate and redundant records removed
Only unique and meaningful entries retained
Dataset ready for further analysis or reporting
