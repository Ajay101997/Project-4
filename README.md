# Project-4
📱 Feature Extraction and Price Prediction for Mobile Phones
📌 Project Overview:

This project aims to predict mobile phone prices (Prize) based on their specifications using machine learning techniques. It also identifies the key features that influence mobile pricing.

🎯 Objectives:

Analyze mobile phone specifications
Perform Exploratory Data Analysis (EDA)
Identify important features affecting price
Apply feature engineering and encoding
Build and evaluate machine learning models

📊 Dataset Description:

The dataset contains mobile phone specifications such as:

RAM
Battery Capacity
Camera (Rear & Front)
Processor
Memory
Mobile Height
AI Lens
Color and Model

Target Variable:

Prize (Mobile Phone Price)

🔍 Project Workflow:

1. Data Exploration
Used head(), info(), describe()
Understood dataset structure

2. Missing Value Check
Checked using isnull().sum()
No missing values found

4. Feature Types
Numerical → RAM, Battery, etc.
Categorical → Model, Color, Processor

5. EDA
Univariate Analysis → Histograms, Countplots
Bivariate Analysis → Scatter plots, Box plots
Multivariate Analysis → Pairplot
Correlation Analysis → Heatmap

6. Outlier Detection
Detected using boxplots
Not removed (real-world data)

7. Feature Engineering
Applied One Hot Encoding

8. Train-Test Split
80% Training, 20% Testing

9. Feature Scaling
Used StandardScaler

10. Model Building
Linear Regression
Random Forest Regressor

11. Model Evaluation
R² Score
MAE
MSE

📈 Model Performance:

Model	R² Score
Linear Regression	0.93
Random Forest	0.86

👉 Linear Regression performed better.

⭐ Feature Importance:

Calculated using Random Forest
Identified key features influencing price

📊 Visualizations:

Correlation Heatmap
Feature Importance Plot
Actual vs Predicted Plot
Residual Plot

💡 Business Impact:

Helps companies predict mobile prices
Identifies key features affecting pricing
Supports data-driven decisions

🛠 Technologies Used:

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

📂 Project Files:

project.ipynb → Full code
varImportance.csv → Feature importance
README.md → Documentation

🚀 Conclusion:

This project demonstrates how machine learning can be used to predict mobile phone prices using their specifications. The analysis also identifies the key features that influence price, helping businesses make better product and pricing decisions.
