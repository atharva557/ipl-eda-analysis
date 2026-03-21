# 🏏 IPL Data Analysis (2008-2020)

## Overview
This project is an end-to-end Exploratory Data Analysis (EDA) of the Indian Premier League (IPL) from the 2008 to 2020 seasons. The goal of this analysis is to uncover trends in scoring, evaluate team dominance, and use statistical hypothesis testing to bust common cricket myths (like the true impact of the toss decision).

## 📊 Key Insights
* **The Dominant Franchises:** Throughout the dataset, the most successful team overall was Mumbai Indians, followed closely by Chennai Super Kings.
* **The Target Runs Trend:** Over the years, the average target score has generally stayed between 150 to 170, with a notable anomaly/spike occurring after the 2022 season.
* **The Toss Decision Myth:** Despite a strong visual preference for teams choosing to field first after 2015, a Chi-Square hypothesis test (p-value: 0.39) mathematically proved that the toss decision actually has no statistically significant effect on winning the match.
* **Feature Engineering:** Created abstract data points like `close_match` and `is_toss_winner_match_winner` to translate human concepts into numerical signals for potential Machine Learning models.

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook / PyCharm
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Statistical Testing:** `scipy` (Chi-Square Test of Independence)

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/atharva557/ipl-eda-analysis.git](https://github.com/atharva557/ipl-eda-analysis.git)