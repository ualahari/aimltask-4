# aimltask-4
Task 4: Classification with Logistic Regression.
# Logistic Regression Classification - Breast Cancer Dataset

## 📌 Objective
Build a **binary classifier** using Logistic Regression to predict whether a tumor is **benign** or **malignant**.

## 📊 Dataset
- **Source**: Breast Cancer Wisconsin dataset (available in `scikit-learn`).
- **Features**: 30 features describing tumor cell characteristics.
- **Target**: Binary classification
  - `0` → Malignant
  - `1` → Benign

## ⚙️ Steps
1. Load dataset from scikit-learn.
2. Train-test split (80/20).
3. Standardize features.
4. Train Logistic Regression model.
5. Evaluate using:
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC curve
6. Tune decision threshold and analyze precision-recall tradeoff.

## 📈 Results
- **Confusion Matrix**: Shows correct and incorrect predictions.
- **Precision**: ~0.98
- **Recall**: ~0.96
- **ROC-AUC**: ~0.99
- **ROC Curve**:
  ![ROC Curve Screenshot](roc_curve.png)

## 🧠 What I Learned
- Logistic Regression is for classification, not regression.
- The **sigmoid function** converts outputs to probabilities between 0 and 1.
- **Precision vs Recall**: Precision focuses on accuracy of positive predictions, Recall focuses on capturing all positives.
- **ROC-AUC**: Evaluates model performance across thresholds.
- Threshold selection depends on application needs (ex: healthcare → high recall is important).

## 🛠 Tools & Libraries
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Google Colab

## 🚀 How to Run
```bash
git clone https://github.com/your-username/logistic-regression-classification.git
cd logistic-regression-classification
