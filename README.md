# 📈 ViralPulse FB — Engagement Analytics & Prediction

An end-to-end **data science and machine-learning project** that analyzes Facebook engagement patterns and predicts whether posts belong to a high-performing group.

The project combines exploratory analysis, feature engineering, supervised learning, and an interactive web report.

**[🌐 View the Interactive Report](https://abdulr2005.github.io/-Face-Book--Engagement-Intelligence/)**  
**[💻 View the Web Report Repository](https://github.com/abdulr2005/-Face-Book--Engagement-Intelligence)**

## 🎯 Project Goal

The analysis investigates what separates ordinary posts from the project's top-performing **"Elite"** group and builds a classifier for that target.

The workflow follows:

**Engagement Data → EDA → Feature Engineering → ML Classification → Insights → Interactive Report**

## 💡 Findings from the Dataset

The project analysis identified several patterns:

- **Posting time:** 7 PM showed substantially higher engagement than the low-performing 2 AM period.
- **Content format:** videos generated far more shares than photos in the analyzed data.
- **Reaction behavior:** Love reactions showed a strong relationship with post virality.
- **Elite group:** the project defined the top-performing segment using a shares-based threshold.

These findings describe patterns in the dataset used for this project and should not be treated as universal Facebook benchmarks.

## 🛠️ Technical Stack

- **Data Analysis:** Python, Pandas, NumPy
- **Machine Learning:** XGBoost, Random Forest, Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Interactive Report:** HTML5, CSS3, JavaScript, Chart.js

## 🤖 Machine-Learning Approach

The predictive task classifies posts into **General** and **Elite** groups after data cleaning and feature engineering.

Among the evaluated approaches, **XGBoost produced the strongest reported result at approximately 92.4% accuracy** in the project experiments.

Accuracy should be interpreted together with the target definition, class distribution, and validation setup rather than as a universal measure of future social-media performance.

## 🌐 Data Storytelling Layer

The analytical results are also presented through a separate interactive report. This makes the project more than a notebook-only analysis by turning model and EDA findings into an accessible visual experience.

[Open the live report](https://abdulr2005.github.io/-Face-Book--Engagement-Intelligence/)

## 📌 Project Takeaway

ViralPulse FB demonstrates a complete workflow from **behavioral data analysis to predictive modeling and web-based data storytelling**.
