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
- Countries with infant mortality > 50 (very high).
- Countries with infant mortality < 10 (very low).
- Countries with life expectancy > 75 years.
- Countries whose name contains the word "Islands".
- Countries with less than 1 physician per 1,000 people (critical shortage).  
- Countries with more than 3 physicians per 1,000 people (efficient health systems).
- Countries with fertility rate > 2.1 (growing population).  
- Countries with fertility rate < 2.1 (shrinking or aging population).
- Countries using the Euro (EUR) and with above-average birth rate.  
- Countries using the US Dollar (USD) and with above-average birth rate.  
- Countries with infant mortality rate above 70.
- Countries with the most frequent birth rate value.

Note:
The mode (most frequent birth rate value) highlights common patterns that may reflect cultural or regional influences.
The minimum and maximum birth rates define the range and help detect potential outliers.
The standard deviation of birth rates measures how much birth rates vary across countries — low values indicate similarity, while high values suggest disparity.

---

## 📈 4.Temporal Trends and Changes
**Objective:** Explore how indicators have evolved over time to detect long-term patterns or shocks.

**Example queries:**
- Countries with declining fertility rate since 2000.
- Countries with a sharp drop in birth rate between 2019 and 2021. 
- Trend of average life expectancy in BRICS vs G7 countries.

---

## 🧠 Skills Demonstrated
- Integrating and transforming data using Pandas.
- Cleaning, parsing, and standardizing datasets for analysis.
- Applying logical filtering and exploratory data analysis (EDA).
- Generating insights on global development and economic trends.
- Documenting analysis for technical clarity and reproducibility.
- Comparing temporal and cross-sectional data using groupby and pivoting.
- Summarizing distributions with statistical metrics (standard deviation, min/max, mode).
- Segmenting indicators through conditional querying and business logic.
- Combining demographic and economic dimensions for multivariate analysis.
- Communicating findings through structured, query-driven data storytelling.

---

## 📚 References
Data provided as part of an institutional data project by Adalab. Sources adapted from international organizations such as the World Bank (2023), United Nations Development Programme (2023), and OECD (2023).

