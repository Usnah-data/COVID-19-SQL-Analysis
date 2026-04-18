# 🦠 COVID-19 SQL Data Analysis Project

## 📌 Project Overview

This project explores global COVID-19 data using SQL to analyze infection trends, mortality rates, and geographic spread. The goal is to transform raw data into meaningful insights that can support public health decisions and data-driven storytelling.

---

## 🎯 Objectives

* Analyze the progression of COVID-19 cases over time
* Compare infection and death rates across countries
* Identify trends, spikes, and patterns in the data
* Calculate key metrics such as mortality rate and growth rate
* Demonstrate strong SQL querying and analytical skills

---

##  Dataset Description

The dataset contains COVID-19 records with the following fields:

* **Date** – Daily reporting date
* **Country/Region** – Location of reported data
* **Confirmed Cases** – Total reported infections
* **Deaths** – Total fatalities
* **Recovered** – Total recoveries

> Note: Data may include cumulative values, requiring transformation for daily analysis.

---

##  Tools & Technologies

* SQL (MySQL / PostgreSQL / SQL Server)
* Excel (for quick validation, optional)
* Power BI (for visualization – optional extension)

---

##  Key Analysis & SQL Techniques

### 1. Time Series Analysis

* Tracked daily and cumulative case growth
* Identified peaks and waves of infection

### 2. Country-Level Comparison

* Ranked countries by total confirmed cases and deaths
* Compared mortality rates across regions

### 3. Mortality Rate Calculation

* Calculated death percentage:

  ```
  (Total Deaths / Total Cases) * 100
  ```
* Highlighted countries with unusually high fatality rates

### 4. Growth Rate Analysis

* Measured daily increase in cases using window functions
* Identified rapid spread periods

### 5. Data Aggregation

* Used `GROUP BY`, `SUM()`, `AVG()` for summarization
* Filtered data using `WHERE`, `HAVING`

### 6. Advanced SQL Concepts

* Window Functions (`ROW_NUMBER()`, `LAG()`)
* Common Table Expressions (CTEs)
* Subqueries for layered analysis

---

## 📊 Sample Insights

* Countries with high population density showed faster spread rates
* Mortality rates varied significantly across regions, indicating differences in healthcare capacity
* Certain periods showed exponential growth, highlighting outbreak waves
* Some countries reported slower recovery rates despite high case counts

---

##  Example Queries

### Total Cases by Country

```sql
SELECT country, SUM(confirmed_cases) AS total_cases
FROM covid_data
GROUP BY country
ORDER BY total_cases DESC;
```

### Death Rate Calculation

```sql
SELECT country,
       SUM(deaths) / SUM(confirmed_cases) * 100 AS death_rate
FROM covid_data
GROUP BY country;
```

---

##  How to Use This Project

1. Import the `.sql` file into your SQL environment
2. Run the queries provided
3. Modify queries to explore additional insights
4. (Optional) Connect to Power BI for visualization

---

##  Key Takeaways

* Strong use of SQL for real-world data analysis
* Ability to clean, transform, and analyze raw datasets
* Experience in deriving actionable insights from data
* Demonstrates portfolio-ready analytical thinking

---

##  Future Improvements

* Build an interactive Power BI dashboard
* Add forecasting models for case prediction
* Integrate real-time API data
* Perform regional and continent-level deep dives

---

## 👤 Author

**Usnah Abass**

---
