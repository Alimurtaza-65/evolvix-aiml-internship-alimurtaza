# Week 1 - Task 2: Linear Regression Model

This directory contains the implementation of **Task 2 (Linear Regression Model)** for Week 1 of the AIML Internship.

---

## 📌 Overview
In this task, we built and evaluated a **Linear Regression** model to predict sales/target values based on feature engineering from aggregated data.

---

## 🛠️ Implementation Details
- **Data Preparation & Feature Engineering:** Extracted temporal features such as `day_of_week` and `month` from dates.
- **Train-Test Split:** Split the dataset into training ($80\%$) and testing ($20\%$) sets using `train_test_split`.
- **Model Training:** Trained a `LinearRegression` model using `scikit-learn`.
- **Evaluation Metrics:** Evaluated performance using:
  - **Root Mean Squared Error (RMSE)**: Measures average prediction error magnitude.
  - **R-squared ($R^2$)**: Measures the proportion of variance explained by features.
- **Model Persistence:** Saved the trained model locally as `linear_regression_model.joblib`.

---

## 📁 Files Included
- [`Week_1_Task_2.ipynb`](./Week_1_Task_2.ipynb): Jupyter/Colab notebook containing data splitting, training, evaluation, and model export logic.
- `linear_regression_model.joblib`: Exported trained model artifact.

---

## 🚀 How to Run
1. Open [`Week_1_Task_2.ipynb`](./Week_1_Task_2.ipynb) in Google Colab or Jupyter Notebook.
2. Execute all cells sequentially.
3. The trained model will automatically be saved as `linear_regression_model.joblib`.
