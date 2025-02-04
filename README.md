# Performance-of-Machine-Learning-Models-in-Predicting-Startup-Valuation

This project explores the limitations of traditional valuation methods, such as Discounted Cash Flow (**DCF**) and Comparable Company Analysis (**CCA**), when applied to **startups**. 

Due to the lack of historical data and high uncertainty, machine learning models offer a more effective solution for predicting startup valuations. The study compares the performance of Random Forest, XGBoost, Gradient Boosting Machines (GBM), Decision Trees, Ridge Regression, Lasso Regression, and Elastic Net using metrics like Normalized Root Mean Squared Error (nRMSE) and R-squared (R2). 

Data from over 2,000 startups, sourced from **Crunchbase**, was processed through 5-fold cross-validation to ensure robust performance. Results indicate that **Random Forest** outperformed other models with the lowest normalised Root Mean Square Error (**nRMSE**) (0.1602) and highest **R2** value (0.3814), demonstrating superior accuracy and robustness. 

**Feature contribution analysis** and **Partial Dependence Plots (PDP)** revealed that key financial variables such as **max funding** and **total VC investment** significantly impact valuations. While regularization-based models provided interpretability, they were less effective in capturing complex relationships. 

The project concludes that ensemble models like **Random Forest** and **XGBoost** are **better suited for startup valuation**, offering more accurate and actionable insights for venture capitalists and entrepreneurs. 
