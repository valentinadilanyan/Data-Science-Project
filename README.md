
# Exploratory Data Analysis (EDA): Stress, Season, and Air Pollution

## 📌 Project Overview
This project presents an **Exploratory Data Analysis (EDA)** aimed at understanding how
**stress levels** vary with **seasonality**, **air pollution exposure**, and **districts**.

The goal is to:
- explore patterns in the data,
- identify variability across groups,
- and generate hypotheses for further analysis.

The project was initially developed in a Jupyter Notebook.



---

## 🛠️ Technologies Used
- **Python 3**
- **pandas** – data manipulation and grouping
- **numpy** – numerical operations
- **matplotlib** – data visualization

---
## 📁 Data Source
The dataset used in this project is publicly available at:
https://www.kaggle.com/datasets/thedevastator/air-pollution-and-mental-health

---
## 🔧 Feature Engineering
As part of the exploratory process, basic **feature engineering** was applied to improve
interpretability:

- **`season`**
  - Derived from date/month information
  - Transforms raw time data into a meaningful categorical feature
  - Enables seasonal comparisons of stress levels

- **`high_pollution`**
  - Binary indicator derived from pollution measurements
  - Distinguishes between high and low pollution exposure
  - Simplifies comparison across groups during EDA

These engineered features are intended for **exploratory and descriptive purposes** and
do not imply causal relationships.

---

## ▶️ How to Run the Project

1. Install dependencies (if needed):
```bash
pip install pandas numpy matplotlib seaborn
```

2. Run the script:

All visualizations will be displayed automatically.

---

## 📊 EDA Highlights
- Seasonal stress distributions
- Stress comparison by pollution exposure
- District-level variability via faceted boxplots
- Identification of outliers and overlapping distributions
- Recognition of sparse Spring data

---

## 🧠 Key Findings
- **Autumn** tends to show higher stress levels, particularly under **high pollution exposure**
  in multiple districts.
- In **Winter**, stress distributions under high and low pollution exposure largely overlap across districts, indicating that seasonal or contextual factors may dominate over pollution effects during this period.
- **Spring data is limited**, preventing strong conclusions.

All findings are **descriptive and exploratory**.
