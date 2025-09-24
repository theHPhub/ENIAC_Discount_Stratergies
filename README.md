# 📊 ENIAC Discount Analysis

> **Analyzing ENIAC’s Apple-compatible product sales to uncover whether discounts boost growth or hurt revenue.**

---

## 📝 Project Overview  

ENIAC, a retailer of **Apple-compatible products**, provided us with a messy dataset containing orders, products, and discounts.  
The objective of this project was to **clean the dataset, analyze trends, and determine whether discounts are beneficial** for the company’s long-term growth.  

We performed **data cleaning, feature engineering, exploratory data analysis, and visualization**, delivering clear insights for stakeholders and investors.  

---

## 🚀 Workflow  

### 1. Data Cleaning & Preparation  
- Removed duplicates & handled missing values  
- Standardized **product categories** (Smartphones, Computers, Accessories, Premium, etc.)  
- Merged **products and brand tables** using SKU codes  
- Created **discount %** and **price segments** (Budget, Medium, High-end, Premium)  

### 2. Feature Engineering  
- Built new metrics:  
  - **Discount bins** (0–10%, 10–20%, …)  
  - **Revenue per order**  
  - **Average discount % per category/month**  

### 3. Exploratory Data Analysis (EDA)  
- Revenue & orders analyzed **over 15 months** (Jan 2017 – Mar 2018)  
- Category- and brand-level performance comparison  
- Identified **top-selling products** and **revenue-driving categories**  

### 4. Key Insights  
- 📉 **Revenue declined despite orders increasing** → discount-heavy strategy might be unsustainable  
- 🔑 ~**92% of orders came from discounted products**  
- 💸 **Budget & Medium products** generated most revenue; **Premium** products sold very little even with high discounts  
- 🏆 Top categories: Smartphones, Computers, Accessories  

### 5. Visualizations  
Created clear and presentable plots using **Seaborn** and **Matplotlib**:  
- 📈 **Monthly Revenue vs Orders vs Discounts** (dual-axis line plot)  
- 🪙 **Discount adoption vs average revenue per order** (bar + line combo)  
- 🎯 **Category & price-segment performance** (stacked bar, box plot)  
- 🏅 **Top products & brands by revenue** (bar charts)  

---

## 🛠️ Technologies & Skills  

- **Python** 🐍  
- **Pandas** → Data cleaning, manipulation, merging datasets  
- **NumPy** → Numerical calculations  
- **Matplotlib & Seaborn** → Data visualization  
- **Google Colab** → Cloud-based coding & collaboration  
- **EDA & Data Wrangling** → Handling missing values, outliers, categorical grouping  
- **Statistical Analysis** → Outlier removal, discount impact evaluation  
- **Business Intelligence** → Translating data into actionable insights  

---

## 📊 Deliverables  

- Cleaned datasets (`orders_qu.csv`, `orderlines_qu.csv`, `products_qu.csv`)  
- Visual reports showing:  
  - Revenue vs Orders trend over time  
  - Category-wise performance  
  - Price-segment analysis  
  - Discount effectiveness  
- Business recommendations for ENIAC stakeholders  

---

## 🎯 Goal  

To provide ENIAC’s investors and leadership with **data-backed insights** into how discounts influence sales, revenue, and customer behavior—helping them design **smarter discount strategies** that balance growth and profitability.  

---

## 📂 Project Structure (suggested)

├── data/ # raw & cleaned CSVs
├── notebooks/ # Colab notebooks for analysis
├── scripts/ # reusable Python scripts
├── visuals/ # saved plots & charts
├── README.md # project documentation (this file)
