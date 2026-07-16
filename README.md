# Global Petrol Price & Consumption Analysis — June 2022

## 📌 Project Overview
This project analyzes global oil consumption patterns, petrol prices, and affordability across **180+ countries** using Python. The raw dataset was cleaned, explored, and visualized to uncover meaningful insights about fuel costs, usage trends, and economic relationships worldwide.

## 🧹 Data Cleaning Steps
- Fixed misaligned row for Côte d'Ivoire
- Removed commas, percentage signs, and converted text-formatted numbers into proper numeric values
- Corrected column names and resolved Unicode/encoding errors
- Standardized data types across all columns for accurate analysis
- Verified and preserved original values while fixing structural issues

## 🔍 Key Insights
1. **United States** leads daily oil consumption at ~19.7 million barrels — more than double China in second place.
2. **Venezuela** has the cheapest petrol globally at **$0.08/gallon**, while **Hong Kong** is the most expensive at **$11.35/gallon**.
3. There is **no strong direct link** between a country’s GDP level and petrol price — wealthy nations can have either very low or very high fuel costs.
4. **Nigeria** sells petrol at **$1.57/gallon** (far below the global average), but lower GDP means only about **1,336 gallons** are affordable per person per year.
5. Heavily subsidized nations (Venezuela, Libya, Iran) show extremely low prices, while high-tax developed regions have the highest rates.

## 📊 Visualizations Included
- Top 10 Countries by Daily Oil Consumption
- Fuel Price vs GDP Per Capita
- 10 Cheapest vs 10 Most Expensive Petrol Prices
- Nigeria vs Selected African Countries Comparison

## 🛠️ Tools & Libraries Used
- Python
- Pandas (Data cleaning & manipulation)
- Matplotlib & Seaborn (Data visualization)
- Jupyter Notebook
- GitHub

## 📁 Files in This Repository
- `Petrol Dataset June 23 2022 -- Version 2.csv` — Original raw data
- `Cleaned_Petrol_Dataset.csv` — Final cleaned dataset
- `Global_Petrol_Analysis.ipynb` — Full code for cleaning, analysis & visualization
- `.png` image files — Generated charts
- `README.md` — Project documentation

