# 🛍️ Shopping Intent Prediction

This project is a machine learning solution to predict whether a user will make a purchase during an online shopping session using the k-Nearest Neighbors algorithm.

## 📊 Dataset

The dataset contains over 12,000 user sessions, each described by:
- Pages visited
- Time spent
- Traffic and device info
- Day of week, month, special events
- Whether the session ended with a purchase (`Revenue`)

## 🔧 Features

- Data loading and preprocessing
- k-NN classifier (k=1) using scikit-learn
- Evaluation using:
  - **Sensitivity (True Positive Rate)**
  - **Specificity (True Negative Rate)**

## 🧠 Technologies Used

- Python
- scikit-learn
- Git/GitHub

## ✅ Results Example

```
Correct: 4094
Incorrect: 838
True Positive Rate (Sensitivity): 39.90%
True Negative Rate (Specificity): 91.13%
```



