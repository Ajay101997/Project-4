# Project-4
Feature Extraction and Price Prediction for Mobile Phones
Project Overview:

This project aims to predict mobile phone prices (Prize) based on their specifications using machine learning techniques. It also identifies the key features that influence mobile pricing.

Objectives:

Analyze mobile phone specifications
Perform Exploratory Data Analysis (EDA)
Identify important features affecting price
Apply feature engineering and encoding
Build and evaluate machine learning models

Dataset Description:

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

Project Workflow:

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
```
Univariate Analysis:
```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/c5dc3f96-1d83-405e-9ca3-bd34fb01ac52" />
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/28f9d214-c193-4968-97b8-a59b82b7a0c2" />

```
Bivariate Analysis:

```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/2a5fe215-4d31-4010-8ddd-d336ea9d3953" />
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/f9fa059c-b088-44dd-aa84-9e34f07ce09c" />

```
Multivariate Analysis:

```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/8de0713d-bcdc-4aaa-9372-8c7f5f5b59a3" />

```
Correlation Analysis:
```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/21e279d1-4fa4-474c-9cae-fed0e93eb813" />

```
7. Outlier Detection (Detected using boxplots):
```
<img width="700" height="1000" alt="image" src="https://github.com/user-attachments/assets/955c7b82-f892-42ad-9988-302de95c28a0" />

```

8. Feature Engineering
Applied One Hot Encoding

9. Train-Test Split
80% Training, 20% Testing

10. Feature Scaling
Used StandardScaler

11. Model Building
Linear Regression
Random Forest Regressor

12. Model Evaluation (Linear Regression):
Linear Regression R2 Score- 0.936841257671227
Linear Regression Mean Absolute Error (MAE)- 1420.3176869716235
Linear Regression Mean Squared Error (MSE)- 4690732.
```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/dcc9fd5c-a0e9-4a08-ba9b-21e2d397220d" />

```

13. Model Evaluation (Random Forest):
Random Forest R2 Score- 0.8616470795008602
Random Forest MAE: 1692.9403878504675
Random Forest MSE: 10275324.485738747

```

<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/cd44c6d2-7692-4050-9fae-3e7fbd1bf46f" />

```

Model Performance:

| Model | R² Score | Performance |
|--------|:--------:|-------------|
| Linear Regression | **0.9368** | Best Performing Model |
| Random Forest Regressor | **0.8616** | Good Performance |

Linear Regression performed better.

Feature Importance:

Calculated using Random Forest
Identified key features influencing price

📊 Visualizations:

Correlation Heatmap:
```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/433c5a20-d209-4299-8ea6-1ab7a42f28e5" />

```
Feature Importance Plot:

```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/84c9100f-3589-4eee-a10a-207aa661843b" />

```

Actual vs Predicted Plot:

```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/33a7440a-09fe-4ea3-8e18-3a5cf95bea79" />

```

Residual Plot:

```
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/ea87b129-07ec-4cb7-b298-4d0efac7b4bd" />

```

Business Impact:

Helps companies predict mobile prices
Identifies key features affecting pricing
Supports data-driven decisions

Technologies Used:

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Conclusion:

This project demonstrates how machine learning can be used to predict mobile phone prices using their specifications. The analysis also identifies the key features that influence price, helping businesses make better product and pricing decisions.
