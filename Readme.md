# Customer Lifetime Value Prediction Project

**Internship Project | Role:** Data Analyst  
**Author:** Paluru Tejasri  
**Date:** June 2025

---

## Overview

This project is about predicting Customer Lifetime Value (CLV) using historical retail data. CLV helps businesses know which customers are most valuable so they can improve retention and sales.  
I worked on cleaning the data, creating RFM features, training a regression model, and visualizing results.

---

## Dataset Details

- **Source:** Kaggle Online Retail Dataset
- **Records:** 541,909 rows
- **Columns:** InvoiceNo, InvoiceDate, Quantity, UnitPrice, CustomerID, Country
- **Format:** Excel (.xlsx)

---

## Steps I Followed

1. Removed missing and cancelled records
2. Created a `TotalAmount` column (Quantity × UnitPrice)
3. Generated RFM table for each customer
4. Trained a Linear Regression model using Recency and Frequency to predict Monetary value
5. Evaluated the model (MAE and RMSE)
6. Visualized Actual vs Predicted CLV and Top 10 Customers
7. Saved outputs as Excel files and PNG images

---

## Tools & Libraries Used

- Python (pandas, numpy, scikit-learn, matplotlib)
- Jupyter Notebook (Anaconda)
- Excel for data storage

---

## What I Learned

While working on this project, I learned how to:
- Clean and prepare large datasets
- Create RFM metrics
- Train regression models for prediction
- Visualize business data
- Export results in different formats

---

## Future Improvements

- Try more advanced models like Random Forest
- Add customer segmentation analysis
- Build dashboards using Power BI or Tableau
- Experiment with time-series forecasting for CLV

---

## Acknowledgement

I thank my internship mentors and team for their support and guidance during this project.

---

## Repository Structure


├── data
│   └── Online_Retail.xlsx                       # Raw dataset
│
├── notebooks
│   └── Customer_LTV_Prediction.ipynb            # Jupyter Notebook with all analysis
│
├── output
│   ├── LTV_predictions.xlsx                     # Predicted LTV values
│   ├── top_10_predicted_customers.xlsx           # Top 10 customers with highest LTV
│   ├── actual_vs_predicted_scatter.png            # Scatter plot of actual vs predicted
│   └── top_10_customers_bar_chart.png                # Bar chart visualization
│
├── report
│   └── Customer_Lifetime_Value_Prediction_project_report.pdf          # Project Report
│
└── README.md                                                              # Project overview and details


##  Contact

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/tejasri-paluru-38782634a) for any questions or collaboration opportunities.
