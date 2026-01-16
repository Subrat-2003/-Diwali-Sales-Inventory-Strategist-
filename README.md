# Diwali Sales & Inventory Strategist   🪔

## 📌 Project Overview
This project involves a detailed Exploratory Data Analysis (EDA) of sales data during the Diwali festival. The primary objective is to analyze purchasing trends across different demographics (gender, age, occupation) and geographies to help businesses optimize their marketing strategies and inventory management.

## 📊 Dataset Description
The dataset contains over **11,000 entries** with the following key attributes:
- **Customer Info**: User ID, Name, Gender, Age Group, Marital Status.
- **Location**: State and Zone.
- **Professional Info**: Occupation and Product Category.
- **Transaction Details**: Number of Orders and Total Amount.

## 🛠️ Data Cleaning & Preprocessing
To ensure data quality, the following steps were performed:
- Removed empty/redundant columns (`Status` and `unnamed1`).
- Handled null values by removing rows with missing 'Amount' data.
- Performed statistical summaries to understand data distribution.

## 📈 Key Insights from EDA
Based on the analysis, here are the dominant trends:
- **Gender**: Female customers outnumber male customers and have significantly higher purchasing power.
- **Age**: The **26-35 years** age group contributes the most to total sales.
- **Geography**: **Uttar Pradesh, Maharashtra, and Karnataka** are the top three states by revenue.
- **Occupation**: Employees in **IT, Healthcare, and Manufacturing** sectors are the most frequent shoppers.
- **Products**: The top-selling categories are **Food, Clothing & Apparel, and Electronics**.

## 💡 Strategic Recommendations
1. **Targeted Marketing**: Focus advertising spend on females aged 26-35 in the top-performing states (UP, Maharashtra, Karnataka).
2. **Inventory Management**: Maintain high stock levels for "Hero Products" (e.g., Product P00265242) and popular categories like Food and Clothing.
3. **Sector Outreach**: Create corporate-specific offers for IT and Healthcare professionals.

## 🚀 Technologies Used
- **Python**
- **Pandas** (Data Manipulation)
- **NumPy** (Numerical Computing)
- **Matplotlib & Seaborn** (Data Visualization)

## 📂 How to Use
1. Clone the repository.
2. Ensure you have the `Diwali Sales Data.csv` file in the same directory.
3. Run the `Diwali_sales_Analysis.ipynb` notebook in any Jupyter environment.
