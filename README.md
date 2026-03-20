# Linear-Regression-Multiple-Variables
# 🏘️ Multivariate Price Prediction (Multiple Linear Regression)

This project expands upon simple linear models by implementing **Multiple Linear Regression** to predict target values based on multiple independent variables. It demonstrates how to handle more complex datasets where a single feature isn't enough to capture the full picture.

---

## 🛠️ The Machine Learning Stack
* **Python**: Core programming.
* **Pandas & NumPy**: For data manipulation and matrix operations.
* **Matplotlib & Seaborn**: For multivariate data visualization and correlation heatmaps.
* **Scikit-Learn**: For the `LinearRegression` model, data splitting, and performance evaluation.

---

## 📊 Project Workflow

### 1. Multivariate Data Analysis
* **Feature Correlation:** Used a **Heatmap** to identify which independent variables have the strongest relationship with the target variable.
* **Scatter Matrix:** Visualized the distribution and relationships between multiple features simultaneously.

### 2. Model Implementation
* **The Equation:** Unlike simple regression, this model solves for:  
  $$y = m_1x_1 + m_2x_2 + ... + m_nx_n + b$$  
  *(Where $y$ is the prediction, $x$ are the various features, $m$ are their respective coefficients, and $b$ is the intercept).*
* **Data Splitting:** Separated the dataset into training and testing sets to validate model generalization.

### 3. Evaluation & Insights
* **Coefficients Analysis:** Examined the weights assigned to each feature to understand their individual impact on the final prediction.
* **Performance Metrics:** Calculated **Mean Absolute Error (MAE)** and **R-squared ($R^2$)** to measure the model's accuracy.

---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git](https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git)
