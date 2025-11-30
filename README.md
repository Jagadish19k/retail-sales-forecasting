# 📊 Capstone Project: Sales Insights & Demand Forecasting for a Retail Chain

### 🕒 Duration: 5–6 Days  
### 👥 Audience: Fresh Graduates (24-week Data Science Program)  
### 🧠 Domain: Retail Analytics / Forecasting  
### 📌 Goal: Analyze retail sales data, extract insights, and build forecasting models.

---

## 🎯 1. Learning Objectives

By completing this project, I gained hands-on experience in:

- ✔️ Data cleaning, transformation & manipulation using **Pandas**
- ✔️ Exploratory Data Analysis using **Matplotlib** & **Seaborn**
- ✔️ Statistical testing (t-test, ANOVA, Mann–Whitney) using **SciPy**
- ✔️ Predictive modeling using **scikit-learn**
- ✔️ Time-series forecasting using **statsmodels**
- ✔️ Business storytelling & dashboard presentation (PPT)

---

## 🏬 2. Business Context

A national retail chain shared 2 years of store-level data.  
Management wants to:

- Identify **key sales drivers**
- Understand **seasonal and holiday demand**
- Predict **sales for the next quarter**
- Make **data-driven inventory & promotion decisions**

This project performs an **end-to-end analysis** covering EDA → Statistics → ML → Forecasting → Insights.

---

## 📂 3. Dataset Description

| Column | Description |
|--------|-------------|
| Date | Week start date |
| Store_ID | Unique store identifier |
| Region | Store region (North/South/East/West) |
| Product_Category | Product category e.g., Electronics, Grocery |
| Product_ID | Unique product identifier |
| Units_Sold | Quantity sold |
| Unit_Price | Price per unit |
| Discount | Discount percentage |
| Revenue | Total sale after discount |
| Holiday_Flag | Holiday indicator (0/1) |

---

## 🚩 4. Problem Statement

### **1️⃣ Descriptive**
- Sales trends across regions & categories  
- Monthly and seasonal patterns  
- Holiday effects

### **2️⃣ Diagnostic**
- Impact of discounts on sales  
- Region-level differences  
- Holiday vs non-holiday performance (validated statistically)

### **3️⃣ Predictive**
- Linear Regression model for weekly sales  
- Time-series forecasting (Holt–Winters)

### **4️⃣ Prescriptive**
- Recommendations for promotions, inventory planning, and operational decisions

---

## 🛠️ 5. Tools & Libraries

- **Python**  
- **Pandas, NumPy** – Data processing  
- **Matplotlib, Seaborn** – Visualization  
- **SciPy** – Hypothesis testing  
- **scikit-learn** – ML models  
- **statsmodels** – Forecasting  
- **python-pptx** – Auto PPT generation  
- **Google Colab / Jupyter Notebook**

---

## 🔍 6. Project Workflow

### 📅 **Day 1 — Data Loading, Cleaning & Merging**
- Loaded 3 CSVs  
- Merged using Store_ID & Date  
- Cleaned missing values  
- Added Year/Month/Week features  
- Saved `Cleaned_Merged.csv`

### 📅 **Day 2 — Exploratory Data Analysis**
- Top store performance  
- Monthly & seasonal trends  
- Correlation heatmap  
- Holiday impact visualization  
- Insights written under each chart

### 📅 **Day 3 — Statistical Analysis**
- t-test for holiday vs non-holiday  
- Mann–Whitney for non-normal samples  
- ANOVA for regional differences  
- Business interpretation of p-values

### 📅 **Day 4 — Modeling & Forecasting**
- Linear Regression  
- Model evaluation: R², MAE, RMSE  
- Top driver identification  
- 12-week Holt–Winters forecast  
- Exported `ts_forecast.csv` & plot

### 📅 **Day 5 — Insights & PPT Generation**
- Executive summary  
- Business recommendations  
- Auto-generated PPT → `Capstone_Report_Enhanced.pptx`

---

## 📈 7. Key Findings & Insights

- Significant **seasonality** and **holiday spikes** in sales  
- Top 10 stores generate most of the revenue → focus allocation here  
- **Discounts increase units sold**, but revenue effect varies by category  
- **Store Size** and **Holidays** are major predictors in the regression model  
- Forecast shows stable-to-rising demand for the next 12 weeks

---

## 🧭 8. Business Recommendations

1. 🔹 Prioritize inventory for top-performing stores  
2. 🔹 Increase stock before holiday weeks  
3. 🔹 Use targeted discounts only on elastic categories  
4. 🔹 Regional assortment should vary with demand  
5. 🔹 Use rolling forecasts for weekly planning  
6. 🔹 Build dashboards for sales + error monitoring

---

## 📊 9. Deliverables

- `Capstone_Final_Notebook.ipynb`  
- `Cleaned_Merged.csv`  
- EDA charts (PNG)  
- Statistical analysis results  
- Regression metrics  
- `ts_forecast.csv`  
- `Capstone_Report_Enhanced.pptx`  
- `README.md` (this file)

---

## 🎬 10. Demo & Presentation (5–7 minutes)

Covers:
1. Data cleaning & merging  
2. Trends & insights (EDA)  
3. Predictive model explanation  
4. 12-week forecast  
5. Business recommendations

---

## 🚀 11. How to Run

Clone repository:

```bash
git clone https://github.com/<your-username>/retail-sales-forecasting.git
cd retail-sales-forecasting


12. License: 

This project is released under the MIT License.
See the LICENSE file for more details.
