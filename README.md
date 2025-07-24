# 🫀 Heart Disease Prediction using Logistic Regression (from Scratch)

This project implements a logistic regression model **from scratch** using **Python** and **NumPy** to predict the presence of heart disease based on various medical attributes. It includes complete **data preprocessing**, **manual feature scaling**, **gradient descent optimization**, and **visualization** of training performance using **Matplotlib**.
---

## 📊 Dataset
The dataset is taken from : https://archive.ics.uci.edu/dataset/45/heart+disease
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.
Dataset attributes:
1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.

---

## 🚀 Model Overview

- Implemented **Logistic Regression** manually without using libraries like `sklearn`.
- Applied **gradient descent** for weight updates.
- Used **sigmoid activation**, binary cross-entropy loss, and custom **accuracy** calculation.
- Applied **manual feature scaling** (mean-std normalization).
- Data split: 80% training, 20% testing.

---

## 📈 Training Results

- **Training Accuracy:** ~88.84%
- **Testing Accuracy:** ~63.93%
- Plots for **loss** and **accuracy** over epochs are generated using `matplotlib`.

---
# Documentation

Project report: [Heart Disease Prediction.pdf](https://github.com/user-attachments/files/20370581/Heart.Disease.Prediction.pdf)

---

## 🧠 Example Prediction

```'python
input_data = np.array([62, 0, 0, 140, 268, 0, 0, 160, 0, 3.6, 0, 2, 2])
# Output: "The Person has Heart Disease" or "The Person does not have Heart Disease"

# Documentation

Project report: [Heart Disease Prediction.pdf](https://github.com/user-attachments/files/20370581/Heart.Disease.Prediction.pdf)
