# PRODIGY_ML_05
# Task-05: Traffic Accident Data Analysis

### Internship: ProDigy Infotech
### Dataset: US Accidents (March 2023)  
Source: [Kaggle - US Accidents Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

---

## 📌 Objective
Analyze traffic accident data to identify patterns related to:
- Road conditions
- Weather
- Time of day  

Visualize accident hotspots and contributing factors.

---

## 📂 Steps Performed
1. **Data Loading**  
   - Loaded essential columns from the dataset (`Severity`, `Start_Time`, `Weather_Condition`, `Start_Lat`, `Start_Lng`, etc.)
   - Limited rows for faster processing in Colab.

2. **Data Preprocessing**  
   - Handled missing values.  
   - Extracted time features (Hour, Day, Month).

3. **Exploratory Data Analysis (EDA)**  
   - Accident distribution by time of day.  
   - Accident distribution by weather conditions.  
   - Accident severity patterns.

4. **Hotspot Visualization**  
   - Plotted accident locations using latitude & longitude with Folium.  
   - Identified urban hotspots.

5. **Summary of Findings**  
   - Evening rush hours show the highest accident frequency.  
   - Rain and fog conditions are associated with more severe accidents.  
   - Hotspots are concentrated in urban areas such as Los Angeles, Dallas, and Houston.

---

## 📊 Key Insights
- **Time of Day:** Evening rush hours (5–7 PM) have peak accident counts.  
- **Weather:** Rain and fog increase accident severity.  
- **Hotspots:** Major cities show concentrated accident clusters.  

---

## 📁 Files in Repository
- `Task-05_Traffic_Accident_Analysis.ipynb` → Jupyter/Colab notebook with code and analysis.  
- `README.md` → Project description and insights.  

---

## ✅ Conclusion
This analysis highlights how weather, road conditions, and time of day contribute to accident severity and frequency. The hotspot visualization provides actionable insights for traffic management and public safety.
