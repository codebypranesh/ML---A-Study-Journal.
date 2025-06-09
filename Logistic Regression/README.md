# 🧪 Logistic Regression: Cancer Prediction

This project applies **Logistic Regression** to classify whether a tumor is **benign** or **malignant** using the **Breast Cancer Wisconsin** dataset.

## 📌 Overview

- **Goal**: Predict cancer diagnosis (Malignant/Benign) based on features like radius, texture, perimeter, area, etc.
- **Dataset**: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data)
- **Model Used**: Logistic Regression (Sklearn)

## 🧹 Data Preprocessing

- Removed non-informative columns (`id`, `Unnamed: 32`)
- Converted diagnosis labels to binary: `M = 1`, `B = 0`
- Standardized the feature values using `StandardScaler`
- Checked for nulls and cleaned the data

## 📊 Exploratory Data Analysis (EDA)

- Distribution plots (`hist`, `line`)
- Correlation analysis with `scatter` plots
- Visualized missing data using a heatmap

## 🧠 Model Training

- Used `train_test_split` with a 70-30 ratio
- Trained a Logistic Regression classifier
- Predicted cancer diagnosis on test data

## 📈 Model Evaluation

- **Accuracy**: `98.24%`
- **Classification Report**:
  - Precision: 0.99 (Benign), 0.97 (Malignant)
  - Recall: 0.98 for both
  - F1-score: 0.98

## 📁 Project Structure


## 🧑‍💻 Author

**Pranesh** – [GitHub Profile](https://github.com/codebypranesh)

---

Feel free to ⭐ the repo if you find it helpful!
