# 📊 Student Performance Prediction using Lasso Regression

## 📌 Project Overview

This project aims to analyze and predict student academic performance using **Lasso Regression**.
The model helps identify the most important factors influencing student scores while automatically removing less relevant features.

---

## 🎯 Objectives

* Predict students' exam scores
* Identify key factors affecting performance
* Perform feature selection using Lasso Regression

---

## 📂 Dataset

The dataset contains student academic and behavioral details such as:

* 📘 Study Hours per Day
* 🏫 Attendance Percentage
* 🎓 Previous GPA
* 📝 Assignment Score
* 📊 Midterm Marks (Target Variable)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* Scikit-learn
* NumPy

---

## 🔄 Workflow

1. Load the dataset from Excel file
2. Explore and understand the data
3. Select relevant features and target variable
4. Split dataset into training and testing sets (80:20)
5. Scale features using StandardScaler
6. Train Lasso Regression model (alpha = 0.5)
7. Predict test data
8. Evaluate model using MSE and R² score
9. Analyze feature importance

---

## 📈 Model Evaluation

* **Mean Squared Error (MSE):** Measures prediction error
* **R² Score:** Indicates model accuracy

---

## 🔍 Feature Importance

Lasso Regression helps in:

* Selecting important features
* Reducing overfitting
* Removing irrelevant variables (coefficients become zero)

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/student-performance-lasso.git
```

2. Navigate to project folder

```bash
cd student-performance-lasso
```

3. Install dependencies

```bash
pip install pandas scikit-learn openpyxl
```

4. Run the Python script

```bash
python main.py
```

---

## 📌 Sample Output

* Displays first 5 rows of dataset
* Shows MSE and R² score
* Prints feature coefficients

---

## 🚀 Future Improvements

* Add more features like sleep hours and internet usage
* Try other models (Ridge, Linear Regression)
* Visualize results using graphs

---

## 👩‍💻 Author

**Prathiba Devendiran**

---

## ⭐ Acknowledgment

This project is created for educational purposes to understand machine learning concepts like regression and feature selection.

---
