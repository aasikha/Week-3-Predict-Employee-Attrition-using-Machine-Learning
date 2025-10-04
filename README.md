# Week-3-Predict-Employee-Attrition-using-Machine-Learning

## 📌 Project Overview

This project aims to predict **employee attrition** (whether an employee will leave the company) using the **IBM HR Analytics Dataset**.
We apply **data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning models** to gain insights and build a prediction system.

The project is structured as a **case study notebook** with explanations, visualizations, and model evaluations.

## 📂 Dataset

* **Source**: [IBM HR Analytics Attrition Dataset (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
* **File used**: `WA_Fn-UseC_-HR-Employee-Attrition.csv`
* Contains demographic, work-life, and performance data for employees.

## ⚙️ Tools & Libraries

* **Python 3**
* **Libraries**:

  * pandas, numpy → Data handling
  * matplotlib, seaborn → Visualization
  * scikit-learn → ML algorithms & evaluation
  * imbalanced-learn → SMOTE for class imbalance
  * XGBoost → Advanced classification

## 🚀 Steps in the Project

1. **Load & Explore Data**
   * Preview dataset, check missing values, data types, and class imbalance.
2. **Data Preprocessing**
   * Encode categorical variables
   * Scale numerical features
   * Handle class imbalance with **SMOTE**
3. **Exploratory Data Analysis (EDA)**
   * Visualize attrition trends across job roles, overtime, salary, age, etc.
4. **Model Building**
   * Logistic Regression
   * Random Forest
   * XGBoost
5. **Evaluation**
   * Accuracy, Precision, Recall, F1-score
   * Confusion Matrix
   * Feature Importance
6. **Insights for HR Teams**
   * Identify key factors influencing attrition (OverTime, JobRole, Age, MonthlyIncome).

## 📊 Results

* **Random Forest** and **XGBoost** outperform Logistic Regression.
* Features like **OverTime, JobRole, Age, and MonthlyIncome** are critical in predicting attrition.
* Helps HR teams design better **employee retention strategies**.

## 📌 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/employee-attrition-prediction.git
   cd employee-attrition-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook in Jupyter or Google Colab:

   * Open `Employee_Attrition_Prediction.ipynb`
   * Execute cells step by step

## 🙌 Acknowledgments

* Dataset: IBM HR Analytics (via Kaggle)
* Libraries: Scikit-learn, Imbalanced-learn, XGBoost


