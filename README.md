# Car Market Trends Analysis with Car Dekho Data

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA) and Data Visualization** on Car Dekho used-car data to identify pricing patterns, market trends, depreciation, and relationships between car attributes.

The analysis examines factors such as **car model, car age, mileage, fuel type, seller type, transmission, and previous ownership** to understand their relationship with resale prices and derive meaningful market insights.

---

## 🎓 Internship Project

This project was developed as part of the **VOIS and Vodafone Idea Foundation CSR Program – 4 Weeks Virtual Internship on Data Analytics**.

---

## 🎯 Objectives

- Analyze used-car market trends and pricing patterns.
- Identify the most frequently listed car models.
- Understand the impact of car age and mileage on selling price.
- Compare selling prices across fuel, seller, and transmission types.
- Analyze the relationship between previous ownership and resale value.
- Calculate depreciation and price retention metrics.
- Identify relationships between numerical variables using correlation analysis.
- Generate meaningful insights to support data-driven pricing and purchasing decisions.

---

## 📂 Dataset

The dataset contains historical Car Dekho used-car information, including:

- Car Name
- Manufacturing Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Previous Owner Count

[Car Dekho Data.xlsx](https://github.com/user-attachments/files/31658258/Car.Dekho.Data.xlsx)

The dataset contains **299 records after duplicate removal and data cleaning**.

---

## 🔍 Data Cleaning & Preparation

The following data preparation steps were performed:

- Examined dataset shape and structure.
- Checked column names and data types.
- Inspected the first and last records.
- Identified and removed duplicate records.
- Checked for missing values.
- Generated descriptive statistics.
- Created derived metrics for further analysis.

### Derived Metrics

The following calculated columns were created:

- **Car Age** = Reference Year − Manufacturing Year
- **Depreciation Amount** = Present Price − Selling Price
- **Depreciation %** = `(Present Price − Selling Price) / Present Price × 100`
- **Price Retention %** = `Selling Price / Present Price × 100`

> **Note:** Since 2018 is the latest year available in this historical dataset, it is used as the reference year for calculating Car Age.

---

## 📊 Data Analysis

### Univariate Analysis

- Top 10 Car Models by Number of Listings
- Number of Cars Listed by Fuel Type
- Number of Cars Listed by Seller Type
- Number of Cars Listed by Transmission Type
- Number of Cars Listed by Previous Owner Count

### Bivariate Analysis

- Average Selling Price by Car Model
- Average Selling Price by Car Age
- Kms Driven vs Selling Price
- Average Selling Price by Mileage Range
- High-Mileage vs Low-Mileage Cars
- Kms Driven vs Depreciation
- Average Depreciation by Mileage Range
- Average Selling Price by Fuel Type
- Average Depreciation by Fuel Type
- Average Selling Price by Seller Type
- Average Selling Price by Transmission Type
- Average Depreciation by Transmission Type
- Average Selling Price by Previous Owner Count
- Average Depreciation by Previous Owner Count

### Correlation Analysis

Correlation analysis was performed to understand the relationships between numerical variables such as:

- Selling Price
- Present Price
- Kms Driven
- Car Age
- Depreciation

---

## 📈 Key Insights

- **Market Composition:** The dataset is dominated by specific car models, with **Petrol cars accounting for 79.9%** of listings, followed by Diesel at 19.4% and CNG at 0.7%.

- **Seller & Transmission:** **Dealers are the primary sellers**, while Manual cars account for **87%** of listings compared with 13% for Automatic cars.

- **Car Model & Price:** Car model has a significant influence on selling price, with **premium models such as Land Cruiser commanding the highest average selling prices**.

- **Car Age:** Newer cars generally have higher selling prices, while **older cars tend to experience greater depreciation**.

- **Mileage & Depreciation:** Mileage does not show a strong linear relationship with selling price, but **depreciation generally increases with mileage**, reaching **70.05% for cars driven 80K+ km**.

- **Fuel Type:** **Diesel cars have the highest average selling prices and lowest average depreciation**, while CNG cars have the lowest selling prices and highest depreciation.

- **Seller Type:** Dealer-sold cars have a **substantially higher average selling price** than individually sold cars.

- **Transmission:** Automatic cars have a **higher average selling price** than Manual cars, although their average depreciation is nearly similar.

- **Ownership:** Cars with **fewer previous owners generally have higher selling prices and lower depreciation**, with depreciation increasing as ownership count rises.

- **Correlation:** **Selling Price and Present Price have a strong positive correlation (0.88)**, while Car Age has a weak negative correlation with Selling Price (-0.23).

---

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

---

## 👩‍💻 Author

Ritika Moolya  
Bachelor of Computer Applications (BCA)  
Interested in Data Analytics, Data Science, and Business Intelligence
