# Traffic Accident Analysis: Uncovering Patterns and Risk Factors



## Project Overview

This project aims to analyze traffic accident data to identify patterns, risk factors, and the influence of environmental and situational conditions on accident severity. The goal is to support road safety improvements through data-driven insights and predictive modeling.

---

##  Objectives

- Analyze key factors contributing to traffic accident severity.
- Perform data cleaning, exploration, and visualization.
- Build and evaluate machine learning models to predict accident severity.
- Provide actionable insights through visualizations and interpretation.

---

##  Dataset Description

The dataset includes the following features:

- **Location**: Start_Lat, Start_Lng, End_Lat, End_Lng, Distance(mi)
- **Time**: Start_Time, End_Time
- **Weather**: Temperature(F), Humidity(%), Wind_Speed(mph), Visibility(mi), Pressure(in), Precipitation(in)
- **Severity**: Target variable indicating accident severity (1 to 4)

---

##  Tools & Technologies

- Python 
- Jupyter Notebook 
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

##  Results Summary

- Found strong influence of visibility, temperature, and time on accident severity.
- Random Forest Classifier provided the best accuracy among models tested.
- Peak accident times were during rush hours and adverse weather conditions.

---

##  Visual Insights

- Heatmaps of correlations
- Bar plots for accident counts by time and severity


---

##  Conclusion

The analysis provided a deeper understanding of how environmental and temporal factors affect accident severity. This can help stakeholders develop more effective safety strategies.

---

Dataset link:https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents?select=US_Accidents_March23.csv
