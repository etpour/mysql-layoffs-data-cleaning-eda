## Data Cleaning & Exploratory Data Analysis

Hi! 
This project is an end-to-end **MySQL data cleaning and exploratory analysis** project based on a real-world global layoffs dataset.

The main goal of this project is to take raw, messy data and turn it into a **clean, structured, and analysis-ready dataset**, then explore it to find meaningful trends and insights.
 -- Dataset
- **Source:** Kaggle – Global Layoffs Dataset  
- **Link:** https://www.kaggle.com/datasets/swaptr/layoffs-2022  
- **Format:** CSV  
- **Description:** Company layoffs data including company name, industry, location, total layoffs, percentage laid off, funding, and dates.

--- Tools 
- MySQL  
- MySQL Workbench  
- SQL  
- CTEs & Window Functions

---

##  Data Cleaning Overview
Data cleaning was performed using **staging tables** to ensure the raw data remained unchanged.

Key steps:
- Created staging tables to safely clean data
- Removed duplicate records using `ROW_NUMBER()`
- Standardized industry and country values
- Converted date fields to proper `DATE` format
- Handled NULL and blank values
- Removed unusable rows and helper columns

The final cleaned dataset is stored in a staging table and used for analysis.

---

## Exploratory Data Analysis (EDA)
After cleaning, exploratory data analysis was performed to better understand the data and uncover patterns.

Some of the questions explored:
- Which companies had the highest number of layoffs?
- Which industries were most affected?
- How layoffs changed over time (yearly & monthly)
- Which countries experienced the most layoffs?
- Rolling total of layoffs over time

Advanced SQL techniques such as **CTEs**, **ranking functions**, and **window functions** were used throughout the analysis.

---

## Author
**Elaheh Tahmasbi pour**

Thanks for checking out this project! :)


