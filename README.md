# 📊 Assignment – Part 4: Data Visualization & Machine Learning

## 👨‍💻 Overview
This project analyses a student performance dataset, creates meaningful visualizations, and builds a machine learning model to predict whether a student will pass or fail.

---

## 📁 Project Structure
python-assignment-part4/
│── part4_visualization_ml.ipynb
│── students.csv
│── README.md

---

## 📊 Dataset

The dataset contains 15 students with the following features:
- Academic scores: math, science, english, history, pe  
- Attendance percentage  
- Study hours per day  
- Target variable: `passed` (1 = Pass, 0 = Fail)

---

## 🔹 Task 1 — Data Analysis

- Generated summary statistics using `describe()`
- Counted pass vs fail students
- Created basic scatter and bar plots
- Built a simple Logistic Regression model

---

## 🔹 Task 2 — Matplotlib Visualizations

Created and saved the following plots:
1. Bar chart — average score per subject  
2. Histogram — distribution of math scores  
3. Scatter plot — study hours vs average score  
4. Box plot — attendance (pass vs fail)  
5. Line plot — math vs science scores  

---

## 🔹 Task 3 — Seaborn Visualizations

- Bar plots comparing math and science scores (pass vs fail)  
- Scatter plot with regression lines (attendance vs avg score)  

**Observation:**  
Seaborn made visualization easier and cleaner compared to Matplotlib, as it directly works with DataFrames and requires less manual styling.

---

## 🔹 Task 4 — Machine Learning

- Model used: Logistic Regression  
- Features:
  - math, science, english, history, pe  
  - attendance_pct  
  - study_hours_per_day  

### Steps:
- Train-test split (80/20)  
- Feature scaling using StandardScaler  
- Model training and evaluation  

### Output:
- Training accuracy and test accuracy  
- Prediction results with correctness check  
- Feature importance visualization  

---

## 🔮 Prediction Example

The model predicts whether a new student will pass or fail based on input features, along with probability scores.

---

## ⚠️ Note

- The dataset is intentionally small (15 samples), so accuracy may vary.  
- The focus is on understanding the workflow, not achieving perfect accuracy.

---

## 🚀 Conclusion

This project demonstrates:
- Data analysis using Pandas  
- Visualization using Matplotlib and Seaborn  
- Machine learning using Scikit-learn  

It provides a complete end-to-end pipeline from data exploration to prediction.
