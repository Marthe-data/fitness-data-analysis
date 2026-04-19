# 📊 Fitness Data Analysis: 75 Hard Challenge

## 🔍 Overview
This project analyzes personal fitness data from Samsung Health to assess the impact of a structured 75-day fitness challenge on daily activity levels.

The analysis focuses on identifying behavioral trends, cleaning real-world data, and quantifying measurable improvements in activity.

---

## 🎯 Key Result
- **Before Challenge:** ~415 meters/day  
- **During Challenge:** ~1259 meters/day  

👉 **~3x increase in daily activity (~200% improvement)**

---

## 📈 Visual Insights

### Average Distance by Day of Week
![Average Distance](images/avg_distance_by_day.png)

### Activity Trend Over Time
![Trend](images/trend_over_time.png)

### Before vs During Challenge
![Comparison](images/before_vs_during.png)

---

## 🧹 Data Cleaning Challenges
Real-world data required significant preprocessing:

- Fixed datetime parsing issues  
- Resolved column misalignment from raw export  
- Removed corrupted data (e.g., calories column)  
- Detected and filtered extreme outliers (e.g., 460,000+ meters/day)  

---

## 📊 Analysis Performed
- Daily aggregation of activity metrics  
- Day-of-week behavioral analysis  
- Time-series trend visualization  
- Before vs during challenge comparison  

---

## 🧠 Key Insights
- Structured programs significantly improve consistency and activity  
- Outliers can drastically distort analysis if not handled properly  
- Physical activity increased ~3x during the 75 Hard challenge
- Weekday activity was more consistent than weekends
- Peak activity occurred on Saturday
- Habit consistency improved significantly during the structured challenge

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

---

## 📁 Project Structure
