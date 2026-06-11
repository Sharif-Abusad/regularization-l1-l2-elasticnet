# 🚀 Regularization Techniques: L1 (Lasso), L2 (Ridge) & ElasticNet

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge\&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=for-the-badge\&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge\&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

This project demonstrates the implementation and comparison of the most widely used regularization techniques in Machine Learning:

* Ridge Regression (L2)
* Lasso Regression (L1)
* ElasticNet Regression
* Overfitting Reduction
* Coefficient Shrinkage
* Feature Selection
* Model Performance Comparison

The notebook provides practical insights into how regularization improves model generalization and prevents overfitting.

---

## 🌟 Project Highlights

✔ Implemented Ridge Regression (L2)

✔ Implemented Lasso Regression (L1)

✔ Implemented ElasticNet Regression

✔ Compared Model Coefficients

✔ Analyzed Overfitting and Underfitting

✔ Evaluated Model Performance

✔ Visualized Feature Importance

✔ Demonstrated Coefficient Shrinkage

---

## 🛠️ Technologies Used

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming Language    |
| NumPy            | Numerical Computation   |
| Pandas           | Data Analysis           |
| Matplotlib       | Visualization           |
| Scikit-Learn     | Machine Learning        |
| Jupyter Notebook | Development Environment |

---

## 📂 Project Overview

The project explores how regularization helps machine learning models:

* Reduce model complexity
* Prevent overfitting
* Improve generalization
* Handle multicollinearity
* Select important features

Three regularization methods are implemented and compared.

---

## 📖 Concepts Covered

### 🔹 What is Regularization?

Regularization is a technique used to reduce model complexity by penalizing large coefficient values.

Benefits:

* Prevents Overfitting
* Improves Generalization
* Produces More Stable Models
* Reduces Variance

---

### 🔹 Ridge Regression (L2)

Ridge Regression adds the squared magnitude of coefficients to the loss function.

Characteristics:

* Shrinks coefficients
* Retains all features
* Handles multicollinearity effectively

Model:

```python
from sklearn.linear_model import Ridge

ridge = Ridge(alpha=1.0)
```

---

### 🔹 Lasso Regression (L1)

Lasso Regression adds the absolute value of coefficients to the loss function.

Characteristics:

* Shrinks coefficients
* Performs feature selection
* Some coefficients become exactly zero

Model:

```python
from sklearn.linear_model import Lasso

lasso = Lasso(alpha=0.1)
```

---

### 🔹 ElasticNet Regression

ElasticNet combines both L1 and L2 penalties.

Characteristics:

* Feature selection
* Coefficient shrinkage
* Balances Ridge and Lasso advantages

Model:

```python
from sklearn.linear_model import ElasticNet

elastic = ElasticNet(alpha=0.1, l1_ratio=0.5)
```

---

## ⚙️ Models Implemented

### 1️⃣ Linear Regression (Baseline)

Used as a benchmark model without regularization.

---

### 2️⃣ Ridge Regression

**Penalty:**

$$ \lambda \sum w_i^2 $$

**Purpose:**

* Reduce coefficient magnitude
* Improve model stability

---

### 3️⃣ Lasso Regression

**Penalty:**

$$ \lambda \sum |w_i| $$

**Purpose:**

* Feature selection
* Simplify model

---

### 4️⃣ ElasticNet Regression

**Penalty:**

$$ \lambda_1 \sum |w_i| + \lambda_2 \sum w_i^2 $$

**Purpose:**

* Combine strengths of Ridge and Lasso

---

## 📈 Evaluation Metrics

Models are evaluated using:

* Mean Squared Error (MSE)
* R² Score

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* Overfitting vs Underfitting
* Importance of Regularization
* Ridge Regression
* Lasso Regression
* ElasticNet Regression
* Feature Selection
* Coefficient Shrinkage
* Model Evaluation

---

## 📁 Repository Structure

```text
regularization-l1-l2-elasticnet/
│
├── Regularization_L1_L2_ElasticNet.ipynb
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/regularization-l1-l2-elasticnet.git
```

Navigate to project folder:

```bash
cd regularization-l1-l2-elasticnet
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```
---

## 👨‍💻 Author

### Abu Sharif

Machine Learning & AI Enthusiast

🔗 GitHub: https://github.com/Sharif-Abusad

🔗 LinkedIn: https://linkedin.com/in/abu-sharif

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is intended for educational and learning purposes.

---

<p align="center">
Made with ❤️ using Python and Scikit-Learn
</p>