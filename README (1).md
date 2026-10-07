# Task 4 – Advanced Analytics & Statistical Modeling

**ApexPlanet Software Pvt Ltd – Data Analytics Internship**

Applies statistical analysis and basic predictive modeling on a Superstore-style sales dataset.

## What's inside
| Section | Techniques |
|---|---|
| 1. Statistical Analysis | Mean, median, mode, std dev, skewness · t-test · Chi-square test · 95% confidence interval · business implications |
| 2. Time Series Analysis | Datetime conversion · daily/weekly/monthly resampling · trend, seasonality, residuals · 3-month moving-average forecast |
| 3. Customer Segmentation | StandardScaler · K-Means · elbow method · PCA 2D plot · cluster profiling & recommendations |
| 4. Predictive Modeling | Target = Profit · 80/20 split · Linear Regression · R², MAE, RMSE · top 3 features |

## Project structure
```
Task4_Advanced_Analytics/
├── Task4_Advanced_Analytics.ipynb
├── requirements.txt
└── README.md
```

## How to run
```bash
pip install -r requirements.txt
jupyter notebook Task4_Advanced_Analytics.ipynb
```
Put your dataset (e.g. `superstore.csv`) in the same folder and set `DATA_PATH` in the notebook.
Expected columns: `Order_Date, Customer_ID, Segment, Region, Category, Sales, Quantity, Discount, Profit`.
If no file is found, the notebook generates a sample dataset so it still runs end-to-end.

## Key findings
*(Update with your results after running on your dataset.)*
- Sales are right-skewed → median is a better "typical order" measure.
- Hypothesis tests: t-test (Profit by Segment) and chi-square (Segment vs Category) – see p-values in the notebook.
- Time series shows upward trend and year-end seasonality.
- 4 customer segments identified with tailored recommendations.
- Linear Regression: R² = __ , MAE = __ , RMSE = __ ; top features: __, __, __.

## Tools
Python · Pandas · NumPy · SciPy · Scikit-learn · Matplotlib · Seaborn

#DataScience #MachineLearning #ApexPlanet
