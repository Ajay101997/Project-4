# Project-4
📱 Feature Extraction and Price Prediction for Mobile Phones
📌 Project Overview

This project focuses on predicting the price (Prize) of mobile phones based on their specifications using machine learning techniques. The aim of the project is to identify the most important features that influence mobile phone prices and build a predictive model to estimate the price.

The project includes data exploration, exploratory data analysis (EDA), feature engineering, model building, and model evaluation.
---
🎯 Objective
The main objectives of this project are:
Analyze mobile phone specifications
Identify important features affecting price
Perform feature extraction techniques
Build machine learning models for price prediction
Evaluate the model performance
---
📊 Dataset Description
The dataset contains specifications of different mobile phones.
Features in the dataset include:
Model
Color
Memory
RAM
Battery Capacity
Rear Camera
Front Camera
AI Lens
Processor
Mobile Height
Target Variable
Prize (Mobile Phone Price)
---
🔍 Project Workflow
1️⃣ Data Exploration
The dataset was loaded and explored using Pandas to understand its structure.
Operations performed:
Viewing first rows of data
Checking data types
Understanding statistical summary
---
2️⃣ Data Preprocessing
Checked for missing values using df.isnull().sum()
No missing values were found in the dataset
Dataset was cleaned and prepared for analysis
---
3️⃣ Exploratory Data Analysis (EDA)
EDA was performed to understand the distribution and relationships between variables.
Univariate Analysis
Histograms were used for numeric features
Count plots were used for categorical features
Bivariate Analysis
Numeric features vs Prize using scatter plots
Categorical features vs Prize using bar plots
Correlation Analysis
A correlation heatmap was created to identify relationships between numeric features and price.
---
4️⃣ Outlier Detection
Outliers were identified using boxplots.
However, they were not removed because they represent real-world mobile specifications.
---
5️⃣ Feature Engineering
Categorical variables were converted into numerical format using One Hot Encoding so that machine learning models could process them.
---
6️⃣ Train Test Split
The dataset was divided into:
80% Training Data
20% Testing Data
This helps evaluate the model on unseen data.
---
7️⃣ Feature Scaling
Feature scaling was applied using StandardScaler to normalize numerical variables.
---
8️⃣ Model Building
Two machine learning models were used:
Linear Regression
Random Forest Regressor
These models were trained to predict mobile phone prices.
---
📈 Model Evaluation
Models were evaluated using:
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Model Performance
Model	R² Score
Linear Regression	0.93
Random Forest	0.86

Linear Regression performed better for this dataset.
---
⭐ Feature Importance
Feature importance was calculated using the Random Forest model to identify which features most strongly influence mobile phone prices.
---
📊 Visualizations
The project includes the following visualizations:
Correlation Heatmap
Feature Importance Plot
Actual vs Predicted Plot
Residual Plot
---
💡 Business Recommendations
Based on the analysis:
Mobile phone prices are influenced by key specifications such as RAM, battery capacity, processor, and camera features.
Companies can use these insights to design competitive mobile phones and optimize pricing strategies.
---
🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
---
📂 Project Files
Project Notebook (.ipynb) → Complete project code
varImportance.csv → Feature importance results
README.md → Project documentation
---
🚀 Conclusion
This project demonstrates how machine learning can be used to predict mobile phone prices using their specifications. The analysis also identifies the key features that influence price, helping businesses make better product and pricing decisions.
