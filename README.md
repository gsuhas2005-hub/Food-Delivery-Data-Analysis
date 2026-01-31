# Food Delivery Data Integration & Analysis

## 📌 Project Overview
This project demonstrates the end-to-end process of integrating and analyzing data from multiple sources (CSV, JSON, and SQL) for a food delivery platform. The goal was to consolidate transactional records with user and restaurant metadata to uncover business-critical insights regarding revenue, customer behavior, and cuisine performance.

## 🛠️ Data Architecture
The analysis combines three distinct data formats:
1. **Orders (CSV):** Transactional data including order IDs, dates, and amounts.
2. **Users (JSON):** Master data for customers, including city and membership status.
3. **Restaurants (SQL):** Master data for restaurant details, cuisines, and ratings.



## 🚀 Key Insights
Based on the analysis of 10,000 orders, here are the major findings:

* **Revenue Leader:** **Chennai** emerged as the top revenue-generating city.
* **Membership Impact:** Gold members account for **50%** of total orders, with an average order value (AOV) of **$797.15**.
* **Cuisine Efficiency:** **Chinese** cuisine has the lowest number of distinct restaurants (120) while maintaining significant revenue contributions.
* **Peak Performance:** Total revenue reached its peak during **Q3 (July–September)**.
* **High Ratings:** **3,374 orders** were placed at restaurants with a rating of 4.5 or higher.

## 💻 Tech Stack
- **Language:** Python
- **Libraries:** Pandas (Data Manipulation), Matplotlib/Seaborn (Visualization), Re (Regex for SQL parsing)
- **Environment:** Jupyter Notebook

## 📂 File Structure
- `food_delivery_analysis.ipynb`: The primary analysis notebook.
- `orders.csv`: Transactional data.
- `users.json`: User profile data.
- `restaurants.sql`: Restaurant metadata.
