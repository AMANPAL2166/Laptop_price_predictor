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
- Source: [Kaggle Housing Dataset](https://www.kaggle.com/)  
- Shape: `1460 rows × 81 columns`
- Target Variable: `SalePrice`
- Key Features: `OverallQual`, `GrLivArea`, `GarageCars`, `TotalBsmtSF`, etc.

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
| Model | MAE | MSE | R² |
|--------|------|------|----|
| Linear Regression | 24500 | 1.2e9 | 0.81 |
| Decision Tree | 21000 | 1.0e9 | 0.85 |
| Random Forest | 18000 | 0.8e9 | 0.89 |

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

## 🔮 Future Work
- Try Gradient Boosting & XGBoost models.  
- Add hyperparameter optimization using GridSearchCV.  
- Perform residual analysis for deeper error insights.

---

## 👨‍💻 Author
**Aman Pal**  
B.S. Student, IIT Patna  
Email: amanp8826@gmail.com  
LinkedIn: [linkedin.com/in/aman--pal](https://www.linkedin.com/in/aman--pal/)
