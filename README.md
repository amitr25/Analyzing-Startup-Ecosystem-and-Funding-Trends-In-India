# 🚀 Analyzing Startup Ecosystem and Funding Trends in India

---

## 📌 Objective

To analyze startup funding trends in India and:

- Identify top industries, cities, and investors  
- Discover yearly and sectoral funding patterns  
- Detect funding outliers and variability  
- Predict funding amounts using machine learning  
- Provide data-driven insights to aspiring founders, investors, and analysts  

---

## 📂 Dataset

**Source:** [Startup Funding in India – Kaggle](https://www.kaggle.com/datasets/sudalairajkumar/indian-startup-funding)

**Key Columns:**

- `Startup Name`, `Industry Vertical`, `SubVertical`, `City Location`, `Investors Name`  
- `Investment Type` (e.g., Seed, Series A), `Amount in USD`, `Date`, `Remarks`

---

## 🔍 Use Cases

- Analyze city- and industry-wise funding patterns  
- Identify most active investors and funding rounds  
- Detect seasonal or annual funding booms/busts  
- Predict funding amount based on sector, city, investor type  
- Help aspiring founders understand investor trends  

---

## 🧹 Section A: Python & Data Cleaning

- Load the dataset, display structure, and inspect datatypes  
- Convert Date to datetime and sort by year  
- Clean `Amount in USD` (remove strings, convert to float)  
- Standardize entries in `City Location`, `Industry Vertical`, and `Investment Type`  
- Add derived columns:
  - Extract year from date  
  - Categorize funding (Low, Medium, High)  
  - Count number of investors from `Investors Name`

---

## 🗃️ Section B: SQL Operations

- Import cleaned data into SQL  
- Write queries to:
  - Top 10 most funded startups  
  - Cities with highest total and average funding  
  - Year-wise count by investment type  
  - Common investor-city combinations  
  - Industries with highest median funding

---

## 📊 Section C: EDA & Statistics

- Bar charts for startup count by city and industry  
- Line chart for funding trend over the years  
- Box plots comparing funding by city  
- Pie chart of funding types  
- Word cloud of investor names  
- Correlation between funding and number of investors  
- Summary stats: mean, median, std dev  
- Coefficient of variation and outlier detection  
- Top 3 sectors post-2018 by median investment

---

## 📈 Section D: Tableau Dashboard

- Interactive filters: industry, city, year, funding type  
- Time-series of yearly funding  
- Avg. funding per industry (horizontal bar chart)  
- Top 10 investors and their sectors  
- Scatter plot: funding vs investors  
- Map view of funding distribution  
- Investor tracker with click-to-view insights

---

## 🤖 Section E: Machine Learning

**Regression Task:**
- Predict `Amount in USD` using:
  - Industry, City, Investment Type, Investors, Year  
- Models:
  - Linear Regression  
  - Random Forest  
  - XGBoost (optional)

**Classification Task:**
- Classify startups as Low/Medium/High funded  
- Encode categorical variables  
- Models:
  - Decision Tree, Logistic Regression, Random Forest  
- Evaluate with accuracy and feature importance  

