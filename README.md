# 🛒 Blinkit Sales Analysis – Business KPI Dashboard

> 📊 A real-world data analytics project focused on retail performance KPIs using Python, Pandas, and Seaborn. This project simulates how a business analyst would derive actionable insights from supermarket sales data to guide decision-making for a company like Blinkit.

![Python](https://img.shields.io/badge/Python-3.9-blue) ![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-brightgreen) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-orange) ![Seaborn](https://img.shields.io/badge/Seaborn-EDA-purple) ![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Project Overview

This project explores Blinkit's retail dataset to extract 15+ key business KPIs, perform visual exploratory data analysis, and generate strategic recommendations. It includes data cleaning, transformation, visualization, and insight-driven storytelling.

---

## 📁 Project Structure

| Folder/File           | Description                                      |
|------------------------|--------------------------------------------------|
| [`notebook/`](notebook)         | Python notebooks for data cleaning & EDA           |
| [`visualizations/`](visualizations) | All KPI plots saved as `.png` images              |
| [`report/`](report)             | Final PDF report with findings & recommendations  |
| [`dataset/`](dataset)           | Raw and cleaned dataset files                     |
| [`requirements.txt`](requirements.txt) | Python packages required to run the project     |
| `README.md`                     | This detailed documentation                       |

---

## 📑 Executive PDF Report

📥 Download: [`Blinkit_KPI_Insights_Report.pdf`](report/Blinkit_KPI_Insights_Report.pdf)  
Includes:
- Executive Summary
- KPI Charts
- Business Recommendations

---

## 📊 Sample KPI Visualizations

### ✅ Total Sales by Product Category
<img src="https://raw.githubusercontent.com/ankan-sxc/Retail-Sales-Analysis-for-Blinkit-Business-KPIs-Data-Driven-Insights/main/visualizations/Screenshot%20(286).png" width="600"/>




### ✅ Sales by Outlet Type
<p align="center">
  <img src="https://raw.githubusercontent.com/ankan-sxc/Retail-Sales-Analysis-for-Blinkit-Business-KPIs-Data-Driven-Insights/main/visualizations/Screenshot%20(286).png" width="600"/>
</p>


### ✅ Visibility vs. Sales Correlation
<p align="center">
  <img src="https://raw.githubusercontent.com/ankan-sxc/Retail-Sales-Analysis-for-Blinkit-Business-KPIs-Data-Driven-Insights/main/visualizations/Screenshot%20(287).png" width="600"/>
</p>


> 🔍 Full set of 15 KPI visuals available in [`visualizations/`](visualizations)

---

## 📈 Key Business KPIs

| # | KPI Name                                | Insight Example |
|----|------------------------------------------|-----------------|
| 1  | Total Sales                              | ₹11.8L total revenue |
| 2  | Avg. Sales per Product                   | Top 5 products dominate |
| 3  | Sales by Item Fat Content                | Low Fat products lead |
| 4  | Sales by Item Type                       | Dairy, Fruits, Snacks top |
| 5  | Sales per Outlet                         | OUT035 highest revenue |
| 6  | Avg. Sales by Outlet Type                | Supermarkets > Grocery |
| 7  | Sales by Outlet Size                     | Medium outlets perform best |
| 8  | Sales by Outlet Age                      | Newer outlets growing faster |
| 9  | Sales by Location Type                   | Tier 3 locations top sales |
| 10 | Sales by MRP Bracket                     | Premium MRP items = high sales |
| 11 | Sales per kg (normalized)                | Top profit per weight unit |
| 12 | Top 5 Visible Items                      | Visibility doesn't guarantee sales |
| 13 | Visibility vs Sales Correlation          | Weak correlation |
| 14 | Sales by Fat Content per Outlet          | Certain outlets specialize |
| 15 | Sales by Establishment Year              | Recent outlets show growth |

---

## 💡 Business Recommendations

- 🧃 Focus on top 5 SKUs for consistent stocking  
- 📍 Expand to Tier 3 locations with highest returns  
- 🛒 Invest more in **Medium-sized Supermarkets**  
- 🧴 Promote **Low Fat** products with better visibility  
- 🧠 Use **MRP-based pricing strategies** to improve profit margins

---

## 🧹 Data Cleaning & Feature Engineering

- Handled missing values in `Item_Weight`
- Standardized inconsistent labels in `Item_Fat_Content`
- Created `Outlet_Age` feature
- Normalized visibility where `0.0` appeared
- Created MRP brackets and per-kg sales metrics

---

## 🛠 Tools & Technologies

- 🐍 Python 3.9
- 📦 Pandas, NumPy
- 📊 Matplotlib, Seaborn
- 📒 Jupyter Notebook
- 🌐 Git & GitHub

---

## 📥 Installation & Usage

```bash
git clone https://github.com/ankan-sxc/Blinkit-Sales-Analysis-Business-KPI-Dashboard-Project.git
cd Blinkit-Sales-Analysis-Business-KPI-Dashboard-Project
pip install -r requirements.txt
jupyter notebook
