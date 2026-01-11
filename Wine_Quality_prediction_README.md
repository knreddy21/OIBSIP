🍷 Wine Quality Prediction Using Machine Learning

📌 Project Overview

This project focuses on predicting wine quality categories (Low, Medium, High) using chemical properties of wine. The objective is to apply data analytics, exploratory data analysis (EDA), and machine learning techniques to build and evaluate classification models that can accurately predict wine quality.


---

🎯 Problem Statement

Wine quality is influenced by multiple chemical attributes such as acidity, alcohol content, sulphates, and sulfur dioxide. Manually evaluating wine quality is time-consuming and subjective.

Goal: To build a machine learning model that predicts wine quality categories based on physicochemical features.


---

📂 Dataset Description

Source: UCI Machine Learning Repository (Wine Quality Dataset)

Type: Structured CSV dataset

Records: Red wine samples

Features: 11 numerical chemical properties

Target Variable: Wine Quality (converted into categories)


🧪 Features Used

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol


🎯 Target Variable

quality_category

Low (0–4)

Medium (5–6)

High (7–10)




---

🛠️ Tools & Technologies

Programming Language: Python

Libraries:

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Data visualization

Scikit-learn – Machine learning models


Environment: Jupyter Notebook



---

🔍 Methodology

1️⃣ Data Preprocessing

Removed unnecessary columns (Id)

Checked and removed duplicate values

Converted numerical quality into categorical labels

Handled outliers using IQR method

Applied feature scaling using StandardScaler


2️⃣ Exploratory Data Analysis (EDA)

Analyzed distribution of numerical features

Boxplots for outlier detection

Correlation heatmap to identify important relationships

Category-wise comparison using boxplots


3️⃣ Feature Engineering

Selected relevant features based on correlation

Encoded categorical target variable using Label Encoding


4️⃣ Model Building

The following classification models were trained and evaluated:

Random Forest Classifier

Gradient Boosting Classifier

Support Vector Machine (SVM)


5️⃣ Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

F1-score



---

📊 Results & Insights

Random Forest achieved the best overall performance

Alcohol and sulphates were the most influential features

Medium-quality wines were the most common category

Proper preprocessing significantly improved accuracy



---

📈 Visualizations Included

Quality category distribution

Feature histograms

Boxplots for outliers

Correlation heatmap

Model accuracy comparison

Feature importance plot



---

✅ Conclusion

This project demonstrates how machine learning can be effectively applied to predict wine quality categories. Through proper data preprocessing, EDA, and model selection, reliable predictions can be achieved. The approach can be extended to other food and beverage quality assessment systems.


---

🚀 Future Enhancements

Hyperparameter tuning for better accuracy

Trying advanced models like XGBoost

Handling class imbalance using SMOTE

Deploying the model using Flask or Streamlit

