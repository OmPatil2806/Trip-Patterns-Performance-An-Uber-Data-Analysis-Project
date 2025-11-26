# 🚗 Uber Trip Data – Exploratory Data Analysis (EDA)

A comprehensive Exploratory Data Analysis (EDA) project on Uber trip data to uncover insights about mileage patterns, trip purposes, temporal behaviors, city-to-city travel trends, and operational abnormalities.  
This project includes data cleaning, feature engineering, anomaly detection, and visual storytelling through advanced charts.

---

## 📌 Project Overview

This project dives deep into a real-world Uber trip dataset, performing extensive preprocessing and analysis to answer key operational and behavioral questions.

Key tasks include:

- Data quality assessment (missing values, anomalies, duplicates)
- Date parsing and duration calculations
- Cleaning and normalizing city names & trip purposes
- Deriving new features (hour, weekday, month, trip type, city pairs, MPM, etc.)
- Outlier detection using statistical methods and mileage thresholds
- Visual pattern analysis using histograms, line charts, bar charts, boxplots, treemaps, and more

The goal is to transform raw trip records into meaningful insights for business decision-making.

---

## 🧩 Problem Statement

Uber stores thousands of trip records daily, but raw data alone does not reveal:

- Why trips occurred  
- Which routes consume the most mileage  
- What time customers travel the most  
- Whether anomalies exist (e.g., unrealistic speeds or durations)  

Without proper EDA, companies cannot optimize routes, identify cost leakages, or understand customer behavior.

---

## 📉 Business Problem

The business needs clarity on:

- Which trip categories drive the highest mileage cost?
- Are certain trip purposes (e.g., meals) abnormally short or inefficient?
- What times or months show peak travel activity?
- Which city pairs are most frequently traveled or longest on average?
- Are there data errors or abnormal trips affecting reporting accuracy?

These insights help in budget planning, route optimization, compliance checks, and resource allocation.

---

## 🛠️ How the Project Solves It

This project builds a complete EDA pipeline:

### ✔️ 1. Data Cleaning
- Fixes invalid dates  
- Handles missing and inconsistent city names  
- Normalizes purpose text into grouped categories  
- Identifies and corrects outliers  

### ✔️ 2. Feature Engineering
- Adds trip duration, miles per minute, and city pairs  
- Extracts month, weekday, hour, and year  
- Flags unrealistic trips (e.g., >3 miles/minute)  

### ✔️ 3. Insights & Visualizations
Answers high-value business questions such as:

- Which trip type consumes the most miles?  
- Are meal trips unusually short?  
- When do meetings cluster?  
- Which months show mileage peaks?  
- What are the most common and longest city routes?  
 
---

## 📊 Visual Insights Covered

- Trip distribution by weekday, hour, month  
- Mileage distribution and outlier detection  
- Purpose-wise miles and frequency  
- City-pair travel patterns (treemap & bar charts)  
- Boxplots for purpose-wise trip distances  
- Miles vs duration relationship  
- Peak month analysis  
- Trip type vs mileage (treemap)  

---

## 📁 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Squarify (Treemaps)  
- Jupyter Notebook / PyCharm  

---

## 🏁 Conclusion

This project successfully transforms raw Uber trip data into actionable business intelligence.  
By cleaning, enriching, and visualizing the dataset, it reveals important patterns in travel behavior, trip efficien

## 👤 Author

**Om Patil**  
📧 Data Science & Machine Learning Enthusiast  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)
