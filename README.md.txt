# Fitness Data Analysis: 75 Hard Challenge

## 📊 Overview
This project analyzes personal fitness data collected from Samsung Health to evaluate behavioral changes in physical activity before and during a structured 75-day fitness challenge.

## 🎯 Objective
To identify trends in daily activity and quantify the impact of a structured fitness program.

---

## 📁 Dataset
- Source: Samsung Health export
- Time range: Jan 2023 – Jul 2024
- Records: 4,000+ rows
- Key feature used: Distance (meters)

---

## 🛠️ Data Cleaning
- Handled datetime parsing issues
- Identified and removed corrupted columns (e.g., calories)
- Fixed column misalignment
- Removed extreme outliers (e.g., 460,000+ meters in one day)
- Aggregated data to daily level

---

## 📈 Analysis

### 1. Activity by Day of Week
- Saturday showed the highest average activity levels

### 2. Trend Over Time
- Clear increase in activity during April–July 2024

### 3. Before vs During Challenge

| Period            | Avg Distance |
|------------------|-------------|
| Before Challenge | ~415 meters |
| During Challenge | ~1259 meters |

👉 ~3x increase in activity (~200% improvement)

---

## 📊 Visualizations
- Average distance by day of week (bar chart)
- Activity trend over time (line chart)
- Before vs during comparison (bar chart)

---

## 🧠 Key Insights
- Structured challenges significantly improve consistency and activity levels
- Data cleaning is critical when working with real-world datasets
- Outliers can heavily distort results if not handled properly

---

## 🚀 Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook