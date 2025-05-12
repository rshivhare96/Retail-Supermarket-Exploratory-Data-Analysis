# 🛒 Retail Supermarket Exploratory Data Analysis

This project performs an **Exploratory Data Analysis (EDA)** on a retail supermarket dataset to uncover actionable insights related to **sales**, **profit**, and **discount** trends across multiple dimensions including geographic regions and product categories. The analysis provides business intelligence to guide **strategic retail decisions**.

---

## 📊 Dataset Overview

The dataset, `SampleSuperstore.csv`, contains **transactional records** with the following key attributes:

- **Geographic Info:** City, State, Region  
- **Order Details:** Ship Mode, Sales, Profit, Discount  
- **Product Info:** Category, Sub-Category  

> ✅ The dataset was clean and well-structured with **no missing values**, enabling seamless analysis and visualization.

---

## 🧹 Data Preprocessing

- ✅ Loaded and inspected the dataset for structure and integrity  
- 🔍 Verified absence of null or missing values  
- 🔄 Converted numerical columns (Sales, Profit, Discount) to appropriate formats  
- 🗂️ Categorized data by region, product category, and shipping mode for analysis  

---

## 📈 Exploratory Data Analysis

The analysis aimed to answer **key business questions** related to profitability, geographic performance, and discount strategies.

### 📦 Shipping Mode Distribution

- Most orders are shipped via **Standard Class**, followed by Second Class.
- Faster shipping options are less common but may impact cost structures.

### 🏙️ Top 10 Cities by Profit and Loss

- **High Profit Cities:** New York City, Los Angeles, Seattle  
- **High Loss Cities:** Philadelphia, Chicago, Houston  
- Highlights **urban profitability contrasts**.

### 🗺️ State and Regional Performance

- **Profitable States:** California, New York, Washington  
- **Unprofitable States:** Texas, Illinois, Ohio  
- The **Western region** leads in overall profitability, while the **Central region** shows significant losses.

### 🛍️ Product Category and Sub-Category Analysis

- **Technology** is the most profitable category; **Tables** in the Furniture category incur high losses.
- **Phones** and **Chairs** stand out in sub-category performance.

### 📉 Discount vs Profit/Sales Correlation

- High discounts often **negatively correlate** with profit.
- A **delicate balance** between offering discounts and maintaining profitability is evident.

---

## 💡 Insights & Recommendations

- 🌍 **Focus on top-performing states** (e.g., California, New York) for strategic expansion.
- 📉 **Minimize operations in consistently unprofitable regions** or analyze underlying causes.
- 🪑 **Reevaluate pricing/stocking of loss-heavy products** like Tables and Bookcases.
- 🎯 Discounts should be **strategically limited** — high discounting often leads to reduced profits without sufficient sales volume gain.

---

## 🚀 Future Work

- Implement **predictive analytics** for future sales and profit estimation.  
- Develop **dashboard visualizations** for dynamic business intelligence.  
- Conduct **seasonality analysis** to optimize inventory and promotions by time of year.
