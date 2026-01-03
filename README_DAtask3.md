Data Cleaning & Preprocessing Project
📌 Project Overview
This project focuses on cleaning and preprocessing a real-world Airbnb dataset to improve data quality and prepare it for effective data analysis and machine learning tasks. Real datasets often contain missing values, inconsistent formats, and outliers, which can negatively impact analytical results.
🎯 Objectives
Identify and handle missing values
Standardize text, date, and numerical formats
Detect and remove outliers
Prepare a clean, structured dataset for analysis
📂 Dataset
Source: Airbnb Open Dataset (Kaggle)
Type: Real-world structured data
Size: ~48,000 records
Key Features: price, room_type, neighbourhood, reviews, last_review
🛠 Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
       Task Breakdown
🔹 Step 1: Data Loading & Exploration
Loaded dataset using Pandas
Checked shape, data types, and basic statistics
🔹 Step 2: Missing Value Handling
Filled categorical columns (name, host_name) using mode
Filled reviews_per_month with 0
Converted last_review to datetime format
Replaced missing last_review values with randomly generated dates within the dataset’s date range
🔹 Step 3: Data Standardization
Converted text columns to lowercase and removed extra spaces
Standardized date format using datetime conversion
Applied Min-Max scaling to numerical columns (price)
🔹 Step 4: Outlier Detection & Removal
Identified outliers in price using the IQR method
Removed extreme values to reduce skewness
📊 Results
All missing values handled appropriately
Text and date formats standardized
Outliers removed for improved data consistency
Final dataset is clean and ready for analysis and modeling
