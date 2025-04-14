# 🚲 Yulu Ride Data Analysis & Hypothesis Testing

This project focuses on **exploratory data analysis (EDA)** and **statistical hypothesis testing** using ride-sharing data from Yulu, a micro-mobility service provider. The goal is to uncover usage patterns, relationships, and statistically significant insights from the data.

---

## 📌 Objective

- Perform detailed **EDA** to understand trends in user behavior and ride patterns.
- Use **hypothesis testing** to validate assumptions and uncover statistically significant relationships in the dataset.

---

## 🧰 Tools & Libraries

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scipy (for statistical testing)
- Statsmodels

---

## 📊 Dataset Overview

The dataset contains information about Yulu rides such as:
- Ride duration
- Start and end times
- Locations
- User types
- Distance covered  
*(Add more fields if applicable)*

---

## 🔍 Key Questions & Hypotheses

- **Do weekdays and weekends show significant differences in ride volume?**  
- **Does average ride duration differ between casual and subscribed users?**  
- **Are longer rides more common during certain hours of the day?**  
- **Is there a significant correlation between ride distance and duration?**

---

## ✅ Techniques Used

### 🧪 Hypothesis Testing
- **Two-sample t-test**
- **ANOVA**
- **Chi-Square test for independence**
- **Correlation tests (Pearson)**

### 📊 Visualizations
- Boxplots, histograms, KDE plots
- Heatmaps and bar charts
- Time series plots for trend analysis

---

## 💡 Insights

- Statistically significant difference in ride durations between weekdays and weekends
- Casual users tend to take longer rides on average
- Peak usage observed in morning and evening commute hours  


---

## 📁 Project Structure

```bash
yulu-hypothesis-analysis/
│
├── data/                  # Raw and cleaned datasets
├── notebooks/             # Jupyter notebooks with full analysis
├── yulu_eda_hypothesis.py # Script version of the project
├── README.md              # This file
└── visuals/               # Charts and plots
