# Elevate-Labs-Task-3
## 🚀 Linear Regression Project

This project demonstrates the implementation of **Simple** and **Multiple Linear Regression** models using **Python**. The objective is to build a regression model to predict a target variable from one or more features and evaluate its performance using key metrics.

---

### 📌 **Objective**

👉 To implement and understand both simple and multiple linear regression using:

* **Scikit-learn**
* **Pandas**
* **Matplotlib**

---

### 🛠 **Tools & Libraries**

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

### 🔑 **Steps Covered**

1️) Imported and explored the dataset

2️) Preprocessed the data:

  • Encoded categorical variables using `pd.get_dummies`
  
  • Converted categorical target to numeric if necessary

3️) Split data into training and testing sets (80/20 split)

4️) Trained a **Linear Regression** model using `sklearn.linear_model.LinearRegression`

5️) Evaluated model performance using:

  • Mean Absolute Error (MAE)
  
  • Mean Squared Error (MSE)
  
  • R² Score

6️) Plotted:

* For simple regression: actual vs predicted with regression line
* For multiple regression: actual vs predicted scatter plot

---

### 📊 **Model Evaluation Output**

```
Model Evaluation Metrics:
MAE: 0.65
MSE: 0.61
R²: 0.03

Intercept: 1.729410322699008
Coefficients:
price: -1.0812521093209416e-07
area: 1.6853813288717875e-05
bedrooms: 0.008917838889712117
bathrooms: 0.06191835191397325
stories: -0.0521609903057707
parking: -0.07631986514306534
mainroad_yes: -0.17331730785575175
guestroom_yes: -0.023373990566529092
basement_yes: -0.1518541587563577
hotwaterheating_yes: -0.038878228407984446
airconditioning_yes: -0.021264636614891898
prefarea_yes: 0.036124063036293966 
```

---

### 📈 **Visualization**

* **Simple Linear Regression:** Regression line overlaid on actual data points
* **Multiple Linear Regression:** Scatter plot comparing actual vs predicted values
* 
![Actual vs Predicted Values (Multiple Regression)](https://github.com/user-attachments/assets/2bbdb944-6ed4-4687-94a3-af4c4401a825)


---

### 💡 **What I Learned**

* How to preprocess and encode mixed-type datasets
* How to build and evaluate linear regression models
* How to visualize and interpret regression results

---

