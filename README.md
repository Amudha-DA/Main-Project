# Synthetic Online Retail Sales and Customer Insight

## Project Overview
This project analyzes a synthetic e-commerce dataset containing 1,000 transactions from 2024 to 2025. The study employs descriptive, diagnostic, predictive, and prescriptive analytics to understand sales performance and customer behavior.

### Key Objectives
* **Exploratory Data Analysis (EDA):** Identify meaningful patterns and trends in e-commerce sales.
* **Data Quality:** Clean and transform raw data by handling missing values and outliers.
* **Customer Behavior:** Analyze purchasing habits across different cities, genders, and age groups.
* **Visualization:** Create informative plots using Python (Matplotlib/Seaborn) and an interactive Power BI dashboard.
* **Actionable Insights:** Derive data-driven recommendations for inventory and marketing strategies.

---

## Dataset Description
The dataset includes the following key features:
* **Customer Info:** ID, Gender, Age, City.
* **Order Details:** Order Date, Quantity, Payment Method (Credit Card, Bank Transfer, Cash on Delivery).
* **Product Info:** Product ID, Category Name (Electronics, Fashion, Home & Living, etc.), Price.
* **Feedback:** Review Scores (1-5).

---

## Analysis Workflow

### 1. Data Pre-processing (Python)
* **Missing Value Treatment:** Handled missing values in `review_score` using median imputation and `gender` using mode.
* **Feature Engineering:** Calculated `total_price` (Price × Quantity) for revenue analysis.
* **Outlier Detection:** Used boxplots to verify data distribution for `price` and `quantity`.

### 2. Exploratory Data Analysis
* **Univariate Analysis:** Distribution of product categories and pricing frequency.
* **Bivariate Analysis:** Relationship between Customer Age and Total Purchase Price, and average spending by payment method.
* **Multivariate Analysis:** Correlation heatmaps and pair plots to identify complex interdependencies between features.

### 3. Power BI Dashboard
The interactive dashboard provides a high-level summary of:
* Total Sales and Quantity Sold.
* Top Performing Cities and Product Categories.
* Customer Segmentation by Gender and Age.
* Payment Method Distribution.

---

## Key Findings & Recommendations
* **Top Categories:** Certain categories like Electronics and Fashion consistently drive higher revenue.
* **Regional Performance:** Most orders are concentrated in specific key cities, suggesting a need for localized stock availability.
* **Customer Preferences:** Male and female customers show distinct preferences in product categories, enabling targeted marketing.
* **Strategy:** Focus on high-performing regions and improve low-performing categories through targeted discounts or repositioning.

---

## Tools Used
* **Python:** Pandas, NumPy, Matplotlib, Seaborn (Data Cleaning & EDA).
* **Power BI:** Dashboarding and Interactive Visualizations.
* **Excel:** Data storage and initial inspections.

---

## Author
**Amudha. N** Batch: TN-DA-ANB11  
Project Domain: Sales and E-Commerce
