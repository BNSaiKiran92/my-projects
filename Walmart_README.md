# Walmart Black Friday Sales Analysis

## Overview
This project analyzes **Walmart’s customer purchase behavior** based on gender, age, marital status, city category, and product categories using a Black Friday dataset of **550,000+ transactions**.  
The goal is to help Walmart understand **spending differences between men and women** and identify **key purchase drivers**.

## Project Structure
- `walmart_data.csv` → Dataset  
- `notebooks/` → Jupyter notebooks with analysis  
- `README.md` → Project documentation  

##  Key Steps
- Data cleaning (no missing values, handled duplicates).  
- Exploratory Data Analysis (EDA):
  - Distribution of age groups, gender, and marital status.  
  - Occupation and product category frequency.  
  - Spending patterns across demographic groups.  
- Outlier treatment (IQR-based winsorization for purchases).  
- Visualization of purchase trends with Seaborn & Matplotlib.  

## Insights
- Majority of customers are **male (~75%)** and in the **26–35 age group (~40%)**.  
- City Category B has the highest representation (**42% of users**).  
- Married customers (~59%) contribute more to overall sales.  
- Top product categories: **Product Category 5, 1, and 8**.  
- **Purchase distribution** shows most customers spend between ₹5,000–₹12,000.  

## Tech Stack
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter/Google Colab  

## Future Scope
- Build predictive models for purchase amount.  
- Segment customers for targeted marketing.  
- Deploy an interactive dashboard for business teams.  

## Author
- **B N Sai Kiran**  
