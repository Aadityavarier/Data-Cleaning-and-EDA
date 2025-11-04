# data-cleaning-and-eda-project
# 📊 Data Cleaning and EDA Project

This project involves **data cleaning and exploratory data analysis (EDA)** on a dataset containing global company layoffs from **March 2020 to March 2023**.  
The work was done entirely using **MySQL** to practice real-world data wrangling, aggregation, and trend analysis skills.

---

## 🧠 Project Overview

The dataset originally came as an Excel file containing information about various companies, the number of employees laid off, and related business details.

The goal of this project was to:
1. **Clean and structure** the raw data to make it analysis-ready.  
2. **Perform EDA** to uncover trends, patterns, and insights related to layoffs during 2020–2023.

---

## 🗂️ Dataset Details

| Column Name | Description |
|--------------|-------------|
| `company` | Name of the company |
| `country` | Country where layoffs occurred |
| `date` | Date of layoff event |
| `sector` | Industry sector of the company |
| `total_laid_off` | Total employees laid off |
| `percentage_laid_off` | Percent of company workforce affected |
| `location` | Specific location (city or region) |
| `stage` | Company funding stage (e.g., Seed, Series A, Public) |
| `funds_raised_millions` | Total funding raised (in millions) |

---

## 🧹 Data Cleaning Steps

Performed using **MySQL**:
- Removed duplicates and null values.  
- Standardized date and string formats.  
- Handled missing values for `funds_raised_millions` and `percentage_laid_off`.  
- Trimmed whitespaces and corrected inconsistent entries.  
- Converted `date` column to proper `DATE` format for analysis.  
- Created a cleaned version of the dataset for visualization and queries.

---

## 🔍 Exploratory Data Analysis (EDA)

Key analyses performed:
- Total layoffs per **year**, **country**, and **sector**.  
- Top companies with the **highest layoffs**.  
- Monthly trends in layoffs from 2020–2023.  
- Correlation between **funding stage** and **layoff severity**.  
- Distribution of layoffs by **continent** and **industry sector**.

---

## 🧾 Files in This Repository

| File | Description |
|------|--------------|
| `data-cleaning-and-eda-project.mysql` | Main SQL script containing all data cleaning and EDA queries |
| `LICENSE` | MIT License for open-source use |
| `README.md` | Project overview and documentation |

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Aadityavarier/data-cleaning-and-eda-project.git
   cd data-cleaning-and-eda-project
