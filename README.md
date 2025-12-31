Survey Data Duplicate Detection and Cleaning Using Python
This project presents a practical data cleaning and deduplication workflow applied to a survey dataset using Python and Pandas. The objective of the analysis is to identify, understand, and systematically remove duplicate records in order to improve data quality and reliability for downstream analytics.
The project begins with an initial exploration of the dataset to detect both exact and near-duplicate rows. Instead of relying only on full-row duplication, the analysis investigates duplicate patterns across key attributes and examines how duplicate entries are distributed across respondent groups such as employment type and country. Visualizations are used to support interpretation and to provide insight into where duplication occurs most frequently.
A strategic approach to duplicate removal is then implemented. Rather than treating every minor variation as a unique record, duplicates are evaluated based on a selected subset of core attributes (MainBranch, Employment, and RemoteWork) that best represent a respondent’s profile. This reflects a realistic, business-driven definition of uniqueness, where data cleaning decisions are made deliberately and with justification.
The workflow includes:
Detecting duplicate records and reviewing their structure
Analyzing duplication trends using grouping and visualization
Defining logical uniqueness criteria using key identifying fields
Removing duplicates in a controlled, documented manner
Verifying and validating the cleaned dataset
This project demonstrates strong competency in data preparation, quality assessment, and analytical reasoning — skills that are critical in real-world data analyst roles. By completing this work, I aimed to strengthen my ability to work with messy datasets, apply structured cleaning methods, and communicate data quality decisions clearly and professionally.
🛠️ Skills & Tools Used
Programming & Data Processing
Python, Pandas, NumPy
Data Cleaning & Transformation
Duplicate detection and deduplication strategy
Subset-based uniqueness logic
Data wrangling and preprocessing
Exploratory & Pattern Analysis
Frequency and profile-based duplicate analysis
Feature similarity assessment
Data Visualization
Matplotlib
Bar and pie charts for distribution insights
Professional & Analytical Skills
Data quality validation
Structured documentation of cleaning decisions
Problem-solving in real-world datasets
Outcome
The final dataset retains only meaningful, unique records while eliminating redundant entries, resulting in a cleaner and more reliable dataset suitable for further analysis or reporting.
 About This Project
This project was completed as part of my ongoing learning and portfolio development in Data Analytics. It reflects my focus on data quality, analytical thinking, and practical Python-based workflows that align with real-world industry expectations.
