# 🏠 House Price Prediction using Machine Learning

## 📘 Overview
This project explores the relationship between various housing features and their market prices using **supervised machine learning algorithms**.  
It aims to identify which features most strongly influence housing prices and how model choice affects predictive accuracy.

---

## 🎯 Objectives
- Understand the regression problem in real-world data.
- Compare classical ML models like **Linear Regression, Decision Tree, and Random Forest**.
- Analyze model performance using proper evaluation metrics.
- Explore how **feature engineering** and **regularization** impact prediction quality.

---

## 🧩 Dataset
- Source: [Kaggle Housing Dataset]([https://www.kaggle.com/](https://www.kaggle.com/datasets/arnabchaki/laptop-price-prediction))  
- Shape: `1303 rows × 12 columns`
- Target Variable: ` Price`

---

## ⚙️ Methodology

### 1. **Data Preprocessing**
- Handled missing values and categorical encoding.
- Performed feature scaling using StandardScaler.
- Split data: 80% training, 20% testing.

### 2. **Model Implementation**
- Implemented:
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  

### 3. **Evaluation Metrics**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 📊 Results
| Model | MAE | R² |
|--------| ------|----|
| Linear Regression |  0.212 | 0.80 |
| Decision Tree | 0.183 | 0.83 |
| Random Forest |  0.159 | 0.88 |
| Ridge Regression |  0.212 | 0.81 |
| Lasso Regression |  0.213 | 0.80 |
| KNN |  0.185 | 0.84 |
| Decision Tree |  0.183 | 0.84 |
| SVM |  0.212 | 0.78 |
 

 

> Random Forest outperformed others due to ensemble learning and variance reduction.

---

## 🧠 Research Insight
This project highlights:
- **Bias-Variance trade-off** between models.  
- **Feature importance analysis** using Random Forest.  
- How **ensemble methods** improve prediction stability.

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

---
 
---

## 👨‍💻 Author
**Aman Pal**  
B.S. Student, IIT Patna  
Email: amanp8826@gmail.com  
LinkedIn: [linkedin.com/in/aman--pal](https://www.linkedin.com/in/aman--pal/)
