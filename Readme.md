# 🚗 Fuel Efficiency Data Visualization Project

This project is part of the ASC23 course assignment, focusing on transport systems, specifically analyzing vehicle fuel efficiency data using Python’s `matplotlib` and `seaborn` libraries. The goal is to visualize and interpret fuel efficiency-related statistics for future AI model use.

---

## 📝 Assignment Overview

The most recent ASC23 considered four systems-based tracks, including:

- Cities
- Urban and rural settlements
- Infrastructure
- ""Transport""

For this assignment, we analyzed a dataset related to vehicles and fuel efficiency. You were expected to:

1. Import and explore the dataset (show 4–10 rows)
2. Visualize the data using:
   - A histogram of CO₂ emissions
   - Two additional histograms (e.g., engine displacement, MPG)
   - A heatmap of correlation between numeric features
3. Interpret*the plots with insights into fuel usage, emissions, and efficiency patterns
4. Identify columns to drop if the goal is to predict the `ghgScore`, based on correlation analysis
5. Export all plots as `.png` files and submit a GitHub repo with all required materials

## ✅ Objectives

- Import and clean a fuel economy dataset (`fuel_econ.csv`)
- Use Matplotlib and Seaborn to generate insightful plots
- Interpret relationships between features
- Identify redundant or less informative features based on correlation

## 🧠 Libraries Used

- pandas
- matplotlib
- seaborn
- numpy


## 📊 Plots Created

- Histogram of CO₂ emissions
- Histogram of Combined MPG (Miles Per Gallon)
- Histogram of Engine Displacement
- Heatmap showing correlation between numeric features


## 🔍 Insights & Interpretation

1. Most vehicles emit CO₂ between a certain range (e.g., 200–400 g/mile), indicating common fuel consumption behavior.
2. MPG and engine size vary, with a strong inverse relationship to CO₂ emissions.
3. The heatmap reveals high correlations between some features, helping us identify redundant columns when modeling for `ghgScore`.



## 🧹 Suggested Columns to Drop

Based on the correlation heatmap, columns such as `barrels08` and `co2TailpipeGpm` may be dropped if predicting `ghgScore`, since they are strongly correlated with `co2`, which is already included.

## Colab link:
https://colab.research.google.com/drive/1THkajRbuHN2TyNDUlpUnMMqzSkXfPHwS?usp=sharing

## Colab Link

You can preview and interact with the notebook via [Google Colab here](https://colab.research.google.com/drive/your-colab-id-here)  


## 📌 Submission Notes

- All cell outputs are visible
- Both .ipynb and image files (.png) are submitted
- Repository includes this `README.md`
