# 📊 Survey Data Duplicate Detection and Cleaning Using Python

## 🧾 Project Overview
This project focuses on detecting and removing duplicate records in a survey dataset to improve data quality before analysis. It simulates a real-world data analyst scenario where datasets often contain repeated, inconsistent, or redundant records.

---

## ✅ What the Project Does
- Detects duplicate and repeated rows in the dataset  
- Analyzes where duplicates occur and how they are distributed  
- Visualizes duplicates by **Country** and **Employment Type**  
- Applies a strategic approach to remove duplicates  
- Retains meaningful records and removes redundant ones  

---

## 🧠 Deduplication Strategy
Instead of deleting only fully identical rows, the project uses a **subset-based uniqueness approach**.

Duplicates are identified using key profile columns:
- `MainBranch`
- `Employment`
- `RemoteWork`

These represent the **core identity of a respondent** and support realistic, business-driven data-cleaning rules.

---

## 🔧 Workflow Steps
1. Load and explore the dataset  
2. Detect duplicate records  
3. Analyze duplicate patterns  
4. Define uniqueness rules  
5. Remove duplicates using selected key columns  
6. Verify dataset after cleaning  

---

## 🛠️ Skills / Tools Used
- Python  
- Pandas & NumPy  
- Data Cleaning & Pre-processing  
- Duplicate Detection & Deduplication Logic  
- Matplotlib Visualisation  
- Analytical Reasoning & Data Quality Validation  

---

## 🎯 Outcome
- Dataset becomes **cleaner and more reliable**  
- Duplicate and redundant records are removed  
- Only **unique and meaningful entries** remain  
- Data is ready for further analysis or reporting  
