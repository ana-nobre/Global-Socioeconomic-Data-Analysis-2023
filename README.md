# 🌍 Global Socioeconomic Data Analysis – 2023  
**Portfolio Project: Business-Oriented Data Analysis of International Development Indicators**

This project presents a structured analysis of global socioeconomic data using two datasets: `world-data-2023-part1.csv` and `world-data-2023-part2.csv`. The data includes a wide range of development and macroeconomic indicators such as GDP, education, health, taxation, employment, and demographics. The objective is to consolidate, clean, and explore the data to extract insights relevant to business strategy, global development, and public policy.

---

## 📁 1. Integration of Multivariate Datasets  
**Objective:** Merge two datasets containing country-level socioeconomic indicators while ensuring consistency and completeness in the resulting dataset.

**Steps:**
- Load both datasets into Pandas DataFrames.
- Identify common columns and evaluate consistency.
- Choose and justify the appropriate merging method (`merge`, `concat`, or `join`).
- Create a unified DataFrame for further analysis.
- Document the integration decisions and technical rationale.

---

## 🧹 2. Data Cleaning and Standardization  
**Objective:** Ensure the dataset is ready for analysis by transforming and standardizing variables and column names.

**Steps:**
- Drop duplicate columns (e.g., "country").
- Normalize column names (lowercase, underscores, no special characters).
- Split the `coordinates` column into separate `latitude` and `longitude` columns.
- Convert percentages and currency values to numeric types.
- Save the cleaned DataFrame for subsequent queries and visualizations.

---

## 🔎 3. Strategic Filtering and Exploratory Queries  
**Objective:** Execute business-relevant queries to identify demographic and economic trends by country.

**Example queries:**
- Countries with infant mortality between 40 and 50 deaths per 1,000 live births.
- Countries with birth rates ≥ 20 and life expectancy > 75 years.
- Countries whose name contains the word "la".
- Countries with more than 5 physicians per 1,000 people.
- Countries with fertility rate > 6.
- Countries using the Euro (EUR) and with above-average birth rate.
- Countries with infant mortality rate above 70.

---

## 🧠 Skills Demonstrated
- Data integration and transformation using Pandas.
- Data cleaning, parsing, and standardization.
- Logical filtering and exploratory data analysis.
- Insight generation for global development and economic trends.
- Technical documentation and reproducibility of results.

---

## 📚 References
- World Bank (2023). *World Development Indicators*.  
- United Nations Development Programme (2023). *Human Development Data*.  
- OECD (2023). *Tax Revenue and Labour Statistics*.  
- Kaggle Datasets (2023). *World Socioeconomic Indicators 2023*.
