# 🏍️ Used Bike Price Analysis

### 📊 Project Overview
This project explores the **used bike market** through Exploratory Data Analysis (EDA).  
It focuses on understanding how **engine capacity, mileage (KM runs), ownership type, and model year** affect resale price.  
The insights help both **buyers and sellers** make data-driven decisions in the used bike market.

---

## 💼 Business Problem
Buyers and sellers often struggle to determine a fair resale price due to variations in usage, model, and location.  
The goal of this analysis is to identify the **key factors** that influence bike resale prices in India.

---

## 🎯 Objectives
- Explore trends and relationships among variables such as **Price, Engine_CC, KM runs, and Buy_Year**.
- Identify how **ownership and location** affect resale value.
- Visualize the impact of **engine capacity and usage** on pricing.
- Provide actionable insights for the resale market.

---

## 📁 Dataset Description
| Column | Description |
|--------|-------------|
| Vehicle Name | Bike brand/model name |
| Model | Variant of the bike |
| Buy_Year | Year of purchase |
| Price | Resale price (in ₹) |
| Engine_CC | Engine capacity |
| No_of_owners | Ownership status |
| KM runs | Kilometers run |
| City | Listing city |
| State | Listing state |
| Vehicle_Type | Manual or Electric |

**Total Records:** 825  
**Source:** Pre-cleaned dataset of used bike listings across India.

---

## 🧹 Data Cleaning
- Removed duplicates and invalid entries.  
- Standardized `Engine_CC` by removing "cc" and handling missing values.  
- Converted numeric columns (`Price`, `KM runs`, `Buy_Year`) to proper types.  
- Cleaned text columns for consistency.  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis
- Most bikes priced between **₹70,000–₹1,20,000**.  
- Majority engines range between **100–350 cc**.  
- Few high-end bikes are priced above ₹1,50,000.  

### 🔹 Bivariate Analysis
- **Engine_CC vs Price:** Strong positive relationship — higher engine capacity → higher resale price.  
- **No_of_owners vs Price:** Single-owner bikes fetch better resale value.  
- **Vehicle_Type vs Price:** Manual bikes dominate (~95% of data).  

### 🔹 Multivariate Analysis
- **Engine_CC** shows the **strongest correlation** with price.  
- **Mileage (KM runs)** is negatively correlated — more usage → lower price.  
- **Newer models** have higher resale value.

---

## 💡 Key Insights
- **Engine capacity**, **ownership**, and **mileage** are the strongest price predictors.  
- **Manual, single-owner bikes** dominate the dataset.  
- **Top listing states:** Maharashtra, Karnataka, Telangana.  
- **Electric bikes** are emerging but remain a small market segment.  

---

## 🧠 Conclusion
Used bike prices depend mainly on **engine size, mileage, ownership, and age**.  
**Newer, low-mileage, single-owner bikes** retain the highest resale value.  
This analysis helps stakeholders in the resale market make informed pricing decisions.

---

## 🧰 Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

