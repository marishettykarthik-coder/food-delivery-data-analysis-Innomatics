# Food Delivery Data Analysis

This repository contains an end-to-end data analysis project performed as part of a hackathon.  
The project focuses on analyzing food delivery order data by integrating multiple data sources
and deriving meaningful business insights using Python and Pandas.

---

## 📌 Project Overview

The objective of this project is to:
- Merge transactional, user, and restaurant datasets
- Analyze user behavior and membership impact
- Study revenue trends across cities, cuisines, and time
- Generate insights using aggregations and visualizations

---

## 📂 Datasets Used

The analysis is based on the following datasets:

- **orders.csv** – Transactional order-level data  
- **users.json** – User information including city and membership type  
- **restaurants.sql** – Restaurant details such as cuisine and ratings  

---

## ⚙️ Technologies & Libraries

- Python  
- Pandas  
- SQLite  
- Seaborn  
- Matplotlib  
- Jupyter Notebook  

---

## 🔄 Data Processing Steps

1. Loaded data from CSV, JSON, and SQL formats  
2. Performed LEFT JOINs using:
   - `user_id` (orders ↔ users)
   - `restaurant_id` (orders ↔ restaurants)
3. Created a final consolidated dataset
4. Generated additional features such as month and quarter
5. Saved the final dataset as `final_food_delivery_dataset.csv`

---

## 📊 Analysis & Visualizations

The notebook includes:
- City-wise and cuisine-wise revenue analysis
- Gold vs Regular membership comparison
- Average order value analysis
- Rating-based performance insights
- Time-based trends (monthly & quarterly)

---

## 📁 Repository Structure
