# 📊 SQL Layoff Data Project – Part 2: Exploratory Data Analysis (EDA)

This is **Part 2** of my layoff data analysis project. After cleaning and preparing the dataset in **Part 1**, I used SQL to perform exploratory data analysis (EDA) to uncover meaningful patterns and trends behind the global wave of layoffs from 2020 to 2023.

---

## 🔍 Objective

To analyze cleaned layoff data using pure SQL and identify:
- Yearly and monthly layoff trends
- Companies most affected by layoffs
- Layoffs by country and company funding stage
- High-risk companies (e.g., those laying off 100% of their workforce)

---

## 🧠 Key Insights

### 1. Mass Layoffs Were Not Random  
Layoffs peaked sharply in **2023**, reflecting wider economic pressures and industry corrections.

### 2. Some Startups Vanished Overnight  
Several companies laid off **100% of their staff**, even after raising millions in funding — proving that capital alone doesn't ensure long-term survival.

### 3. The US Led in Layoffs — But Not Always Proportionally  
While the **United States** had the highest total layoffs, startups in other regions experienced deeper internal cuts when measured by **percentage laid off**.

### 4. 📌 Layoffs by Company Stage — A Surprising Breakdown  
Contrary to expectations, **Post-IPO companies** had the highest number of layoffs, followed by **acquired firms**, and **Series C/D startups**. Even **Seed** and **Series A** companies were affected, showing layoffs impacted all stages.

### 5. Rolling Monthly Layoff Trend  
Using a **rolling monthly total**, layoffs were shown to build steadily from **March 2020**, slow down in 2021, then surge again through 2022, peaking in **early 2023** with over **340,000 total job cuts**.

### 6. Top Companies by Year  
By ranking companies using SQL window functions, the top 5 most affected companies were identified for each year:
- **2020**: Uber, Booking.com, Groupon  
- **2021**: Bytedance, Katerra, Zillow  
- **2022**: Meta, Amazon, Cisco  
- **2023**: Google, Microsoft, Ericsson

---

## 🛠️ SQL Concepts Used

- Common Table Expressions (CTEs)
- Aggregation (`SUM`, `AVG`)
- Window Functions (`DENSE_RANK`, `OVER`)
- Date Transformations
- Rolling Totals
- Grouping & Filtering

---

## 📁 Files

- `Exploratory Data Analysis.sql` – All SQL queries used for EDA
- `layoffs_staging2` – Cleaned dataset used for analysis (from Part 1)

---

## 📽️ Project Series

- **Part 1**: [Data Cleaning & Preparation](#) *(video/post link if available)*
- **Part 2**: Exploratory Data Analysis (this repo)
- **Part 3**: *(Coming Soon)* – Visualizing the results with Power BI/Tableau

---

## 🤝 Let's Connect

