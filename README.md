# 🏡 California Housing Price Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Project Overview
This project solves a regression problem using the California Housing Dataset. The goal is to predict the median house value of a district based on eight census features, including Median Income, House Age, and Average Rooms.

I conducted a comparative analysis between **Linear Regression** and **Random Forest Regressor** to identify the most effective model for real estate valuation.

---

## 📊 Key Findings from EDA
* **Median Income** is the strongest predictor of house prices (Correlation: 0.68).
* Features like "Average Bedrooms" showed weak correlation, suggesting location and income are more significant drivers of price than size alone.

*(Note: Upload your Heatmap image here)*
![Correlation Heatmap](path_to_heatmap.png)

---

## 🛠 Model Performance
I evaluated models using **R² Score** (Goodness of Fit) and **MAE** (Mean Absolute Error).

| Model | R² Score | Mean Error ($) | Conclusion |
| :--- | :--- | :--- | :--- |
| **Linear Regression** | ~0.60 | ~$50,000 | Fails to capture non-linear market trends. |
| **Random Forest** | **~0.80** | **~$32,000** | **Significantly outperforms** by capturing complex interactions between features. |

### Visualization of Results
The scatter plot below demonstrates the Random Forest model's ability to hug the "perfect prediction" line much closer than the linear model.

*(Note: Upload your Scatter Plot here)*
![Prediction vs Reality](path_to_scatter_plot.png)

---

## 🚀 How to Run
1. Clone the repo.
2. Install requirements: `pip install pandas scikit-learn matplotlib seaborn`
3. Run the notebook `Housing_Price_Prediction.ipynb`.

---
*Author: [Your Name]*
