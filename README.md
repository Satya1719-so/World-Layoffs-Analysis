# 🌎 World Layoff Data Cleaning & Analysis (SQL + MySQL)

This project focuses on **cleaning**, **transforming**, and **analyzing** global layoffs data using **MySQL**.  
It involves handling missing values, removing duplicates, and performing **exploratory data analysis (EDA)** to identify trends across companies, industries, and countries.

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Steps Performed](#steps-performed)
- [Key Insights](#key-insights)
- [How to Use](#how-to-use)
- [Sample SQL Queries](#sample-sql-queries)
- [Author](#author)
- [License](#license)

---

## **Project Overview**
This project uses SQL to analyze global layoffs between various companies and industries.  
The analysis involves:
- **Data Cleaning** → Fixing null values, standardizing formats, and removing duplicates.
- **EDA** → Understanding trends across **companies**, **industries**, **countries**, **funding stages**, and **years**.
- **Insights** → Identifying top affected sectors and companies.

---

## **Dataset**
- **File:** `layoffs.csv`
- **Columns:**
    - Company  
    - Location  
    - Industry  
    - Total Laid Off  
    - Percentage Laid Off  
    - Date  
    - Stage  
    - Country  
    - Funds Raised (Millions)
- **Source:** Publicly available layoffs dataset.

---

## **Project Structure**


---

## **Objectives**
- Clean and preprocess the dataset.
- Handle missing, inconsistent, and duplicate data.
- Perform exploratory data analysis (EDA).
- Identify trends and insights based on:
    - Companies
    - Industries
    - Countries
    - Funding stages
    - Yearly patterns
- Create rolling totals for time-based analysis.

---

## **Technologies Used**
- **Database**: MySQL  
- **Language**: SQL  
- **Dataset Format**: CSV  
- **Key Concepts**:
    - Data Cleaning
    - Window Functions
    - Aggregation & Grouping
    - Ranking
    - Rolling Totals

---

## **Steps Performed**

### **1. Data Cleaning (`world_layoff_project.sql`)**
- Removed duplicates using **ROW_NUMBER()**.
- Standardized company names and industries.
- Handled missing and blank values.
- Fixed inconsistent date formats.
- Converted data types for analysis.

### **2. Exploratory Data Analysis (`world_layoff_data_analysis.sql`)**
- Found **maximum layoffs** by company.
- Identified **industries** most impacted.
- Performed **country-wise analysis**.
- Calculated **yearly layoff trends**.
- Ranked top 5 companies with highest layoffs per year.
- Computed **rolling totals** to observe month-wise patterns.

---

## **Key Insights**

📌 **Top Companies** — Certain big tech companies had the highest layoffs.  
📌 **Industries Affected** — Sectors like **tech**, **crypto**, and **retail** saw significant layoffs.  
📌 **Country Trends** — The U.S. reported the maximum layoffs overall.  
📌 **Funding Impact** — Startups in early funding stages were impacted more than established companies.  
📌 **Yearly Patterns** — Layoffs peaked in specific years due to economic slowdowns.

---


