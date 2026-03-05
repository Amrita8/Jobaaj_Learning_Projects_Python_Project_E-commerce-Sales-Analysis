# Jobaaj_Learning_Projects_Python_Project_E-commerce-Sales-Analysis
This README file provides an overview of the **E-commerce Sales Analysis** project conducted in the provided Jupyter Notebook.

---

# Amazon India Sales Analysis

## 📌 Project Overview

This project performs an exploratory data analysis (EDA) and performance assessment of e-commerce sales data from Amazon India. The goal is to uncover sales trends, analyze fulfillment methods, evaluate product performance, and provide data-driven business recommendations to improve customer satisfaction and operational efficiency.

## 🗂️ Dataset Description

The analysis utilizes the `sales_dataset.csv` file, which contains approximately 109,661 records and 23 columns. Key data points include:

* **Order Details**: Order ID, Date, Status.
* **Logistics**: Fulfilment (Amazon vs. Merchant), ship-service-level, ship-city, ship-state.
* **Product Information**: Category, Style, SKU, Size, and Quantity.
* **Financials**: Amount and Currency (INR).
* **Customer Segment**: B2B vs. B2C.

## 🛠️ Tech Stack

* **Python**: Primary programming language.
* **Pandas & NumPy**: For data manipulation, cleaning, and statistical calculations.
* **Matplotlib & Seaborn**: For creating visualizations like bar charts, histograms, and trend lines.

## 📊 Key Analysis & Insights

### 1. Sales & Fulfillment Analysis

* **Valid Orders**: The study focused primarily on "shipped" orders to ensure accurate financial and logistical reporting.
* **Fulfillment Performance**: Comparison of fulfillment types (Amazon-fulfilled vs. Merchant-fulfilled) to evaluate shipping efficiency.

### 2. Product & Category Trends

* **Category Leadership**: Identification of top-performing categories such as **Set**, **kurta**, and **Western Dress**.
* **Top SKUs**: Visual analysis of the most popular SKUs by both quantity sold and total revenue generated.

### 3. Geographical & Segment Insights

* **Regional Demand**: Breakdown of sales by city and state to identify high-growth zones (e.g., Maharashtra, Karnataka, Tamil Nadu).
* **B2B Performance**: Analysis of the small but distinct B2B segment compared to standard consumer sales.

## 📈 Conclusions & Business Recommendations

* **Logistics Improvement**: Addressing low customer satisfaction linked to late deliveries and incorrect orders.
* **Marketing Strategy**: Using B2B vs. B2C insights to tailor marketing campaigns and product offerings specifically to each segment.
* **Operational Challenges**: Managing cancellation rates and streamlining returns processes based on observed status trends.

## 📖 How to Run

1. **Clone** the repository.
2. Install dependencies: `pip install pandas numpy seaborn matplotlib`.
3. Place `sales_dataset.csv` in the project root or update the `path` variable in the notebook.
4. Run the cells in `Amrita_Saha_Gupta_test.ipynb` to view the full analysis.

---

*This analysis was developed to demonstrate proficiency in retail data analytics and business intelligence using Python.*
