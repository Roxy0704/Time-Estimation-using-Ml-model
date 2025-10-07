# 🚴‍♂️ Time Estimation Capstone Project

## Overview
This project aims to **predict food delivery time** based on multiple real-world factors such as **traffic density, weather conditions, vehicle type, and order details**.  
By building a machine learning model, the project provides a data-driven approach to estimate delivery time more accurately, helping delivery platforms optimize operations and improve customer satisfaction.

---

## Objective
To develop a predictive model that estimates the **delivery time (in minutes)** of an order using various influencing features such as:
- Road traffic density  
- Weather conditions  
- Type of order and vehicle  
- Delivery person attributes  
- City and festival indicators  

---

## Machine Learning Workflow
1. **Data Understanding & Exploration**
   - Loaded and inspected raw datasets.
   - Handled missing and inconsistent data.
   - Conducted exploratory data analysis (EDA) using visualizations.

2. **Data Preprocessing**
   - Categorical encoding using `OneHotEncoder`.
   - Feature scaling using `StandardScaler`.
   - Outlier detection and handling.
   - Feature selection based on correlation and importance.

3. **Model Building**
   - Implemented multiple ML models such as:
     - Linear Regression  
     - Random Forest Regressor  
     - Gradient Boosting Regressor  
   - Evaluated model performance using:
     - R² Score  
     - Mean Absolute Error (MAE)  
     - Mean Squared Error (MSE)

4. **Model Evaluation**
   - Compared training and testing performance metrics.
   - Selected the best model based on accuracy and generalization capability.

5. **Result Visualization**
   - Visualized performance metrics and feature correlations using:
     - `Matplotlib` and `Seaborn`.

---

## Tech Stack
- **Language:** Python  
- **Libraries:**
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib  
  - seaborn  

---
## 🏁 Conclusion
This project demonstrates the power of **machine learning in optimizing delivery operations**.  
By leveraging historical data and predictive modeling, it provides valuable insights into factors influencing delivery time — a crucial aspect of efficient logistics and customer satisfaction.
