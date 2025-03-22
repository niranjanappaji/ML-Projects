# Life Expectancy Prediction using Linear Regression

### Overview
This project analyzes the WHO Life Expectancy dataset using Linear Regression models to predict life expectancy based on various health, economic, and demographic factors.

### Dataset

File: Life Expectancy Data.csv
Source: WHO (World Health Organization)

### Columns:
- Life expectancy: Target variable
- Adult Mortality, infant deaths, Hepatitis B, GDP, Schooling, etc.
22 features in total

### Dependencies
Ensure you have the following Python libraries installed:
pip install numpy pandas matplotlib seaborn scikit-learn

### Steps in Analysis

- Data Preprocessing:
- Handle missing values using imputation techniques.
- Scale numerical features using StandardScaler.
- Encode categorical variables.

### Exploratory Data Analysis (EDA):
- Statistical summaries and visualizations.
- Correlation analysis to identify key features.

### Modeling:
- Train-test split of the dataset.
- Linear Regression, Ridge, and Lasso models are implemented.

### Evaluation:
- RMSE (Root Mean Squared Error)
- R² Score (Coefficient of Determination)

### Usage
Run the Jupyter Notebook 02_LinearRegression_WHO_LifeExpectancy.ipynb step by step to execute the analysis.

### Results
The best model is selected based on RMSE and R² score.
Ridge and Lasso regression help in feature selection and improving model performance.

