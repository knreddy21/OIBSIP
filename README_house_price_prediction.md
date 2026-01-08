🏠 House Price Prediction using Linear Regression

📊 Project Overview

This project focuses on building a predictive model using Linear Regression to estimate house prices based on key numerical features. It is part of a Data Analytics – Level 2 project and demonstrates the end-to-end data analysis and machine learning workflow.


---

🎯 Objective

To predict house prices using relevant features and gain hands-on experience in:

Data preprocessing

Exploratory Data Analysis (EDA)

Feature selection

Model training and evaluation

Result visualization



---

📁 Dataset

Source: Housing Price Dataset

Total Records: 545

Total Features: 13

Target Variable: price


Selected Features

area

bedrooms

bathrooms



---

🔍 Exploratory Data Analysis (EDA)

Checked dataset structure and data types

Verified no missing values

Checked and removed duplicate records

Analyzed data distribution and correlations

Visualized relationships using plots and heatmaps



---

⚙️ Model Building

Algorithm Used: Linear Regression

Library: scikit-learn

Data Split:

Training: 80%

Testing: 20%



from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X_train, y_train)


---

📈 Model Evaluation

The model performance was evaluated using standard regression metrics:

Metric Description

MSE Mean Squared Error
RMSE Root Mean Squared Error
R² Score Variance explained by the model


📌 Insight:
The model explains approximately 46% of the variance in house prices, indicating moderate performance.


---

📉 Visualization

Actual vs Predicted House Prices scatter plot

Helps understand prediction accuracy and model behavior



---

🧠 Key Insights

House price has a strong relationship with area and bathrooms

Model performance decreases for high-priced houses

Limited features result in underfitting

Adding categorical and location-based features can improve accuracy



---

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn



---

📌 Learning Outcomes

Understanding of Linear Regression concepts

Practical experience with real-world data

Ability to evaluate and interpret model performance

Improved data visualization skills



---

🚀 Future Improvements

Include categorical features (location, furnishing status, amenities)

Apply feature scaling

Try advanced models (Ridge, Lasso, Random Forest)

Hyperparameter tuning



---

👤 Author

Nani Nani
Data Analytics Student


---

📎 License

This project is for educational purposes only.
