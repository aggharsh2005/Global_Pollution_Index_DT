# 🌍 Pollution Severity Classification

This project classifies countries into pollution severity categories (**Low**, **Medium**, **High**) using machine learning models based on pollution levels, energy consumption, and environmental indicators.

---

## 📌 Objective

To build a classification system that predicts pollution severity, enabling actionable insights for policy making and energy reforms.

---

## 🧠 Models Used

- Naive Bayes Classifier
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

---

## 📊 Results Summary

| Model          | Accuracy | F1 Score | Key Insight                      |
|----------------|----------|----------|----------------------------------|
| Naive Bayes    | 75%      | 0.81     | Better at classifying "Medium"  |
| KNN (K=2)      | 93.33%   | 0.90     | Ignores minority classes         |
| Decision Tree  | 93.33%   | 0.90     | Fails on multi-class balancing   |

---

## 📈 Insights & Recommendations

- Class imbalance is a key issue.
- High pollution countries dominate dataset.
- Energy consumption is directly linked to pollution severity.
- Recommend stricter emission controls and promotion of renewable energy.

---

# 🛠️ Installation

pip install -r requirements.txt

## If using .py
python model_training_script.py

## If using .ipynb
Open with Jupyter Notebook or VS Code and run all cells.


