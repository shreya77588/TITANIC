# 🌸 Iris Species Classification - Machine Learning Project

 📘 Overview

This project demonstrates a machine learning pipeline for classifying iris flowers into one of three species: **Setosa**, **Versicolor**, or **Virginica**. Using the classic "Iris dataset", the notebook performs data preprocessing, exploratory analysis, model training, and evaluation to achieve high accuracy.

---

# 📂 File Description

- `IRISP.ipynb`: Jupyter notebook containing the full workflow for:
  - Data loading and inspection
  - Handling missing values (if any)
  - Feature importance analysis
  - Model training using Logistic Regression
  - Evaluation using accuracy, precision, and a confusion matrix

---

# 📊 Dataset Details

The dataset contains 150 entries with 5 columns:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species` (Target class)

All features are numerical, and the target is categorical with 3 classes.

---

#⚙️ Techniques Used

- "Data Preprocessing": Checked for missing values and normalized numerical data.
- "Feature Importance": Identified key features contributing to species classification.
- "Model": Logistic Regression
- "Evaluation Metrics":
  - Accuracy (achieved 100% on test data)
  - Precision
  - Confusion Matrix

---

# ✅ How to Run

1. Install required packages (if not already installed):
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
2. Launch Jupyter Notebook:
jupyter notebook IRISP.ipynb
3.Run the cells to train and evaluate the model.
# 📈 Results

✅ Accuracy: 100.00%
The model performs exceptionally well, likely due to the clear separation between iris species in the dataset.
