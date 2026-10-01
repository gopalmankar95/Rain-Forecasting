# Rain-Forecasting
Developed monthly rainfall forecasting model for Mumbai to optimize reservoir planning , improve allocating decisions , cut costs, and  ensure reliable supply

## Objectives
- Analyze historical rainfall data
- Identify yearly and seasonal rainfall patterns
- perform data cleaning and preprocessing
- perform Exploratory Data Analysis(EDA)
- Create meaningful rainfall- related features
- Build Machine Learning models for rainfall forecasting
- Compare Model Performance

## Dataset
- Year
- January Rainfall
- February Rainfall
- March Rainfall
- April Rainfall
- May Rainfall
- Jun Rainfall
- July Rainfall
- August Rainfall
- September Rainfall
- October Rainfall
- November Rainfall
- December Rainfall
- Total Rainfall

### Feature Engineering
  - Winter Rainfall
  - Summer Rainfall
  - Monsoon Rainfall
  - Post-Monsoon Rainfall
  - Average Rainfall
  - Maximum Rainfall
  - Minimum Rainfall
  - Rainfall Standard Deviation
  - Previous Year Rainfall
  - Previous 2-Year Rainfall
  - Previous 3-Year Rainfall
  - 3-Year Rolling Mean
  - Rainfall Range
  - Monsoon Ratio
  - Year Passed
  - Year Squared
  - Rainfall Category
 
## Exploratory Data Analysis
EDA was performed to understand rainfall pattern and relationships.

### EDA Activities
- Dataset Overview
- Missing Value Analysis
- Duplicated Value Analysis
- Outlier Analysis
- Monthly Rainfall Analysis
- Year-Wise Rainfall Analysis
- Seasonal Rainfall Analysis
- Correlation Analysis
- Rainfall Trend Analysis

## Data Preprocessing
- Data Cleaning
- Handling Missing Values
- Duplicate Checking
- Feature Engineering
- Outlier Analysis
- Data Transformation
- Train-Test-Split

 ## Model Evaluation
 The Models were evaluated using
 - Mean Absolute Error (MAE)
 - Root Mean Squared Error (RMSE)
 - R 2 Score

### Model Performance
| Model| MAE| RMSE | R2 Score |
|---|---:|---:|---:|  
| Linear Regression | 31.18 | 35.05 | 1.00 |
| Random Forest | 43.95 | 67.23 | 0.98 |
| Gradient Boosting | 23.78 | 42.26 | 0.99 |
| LSTM | 50.21 | 59.81 | -0.11 |

## Model Result
- The gradient boosting model should be selected for further tuning or deployment as it consistently provides the most         accurate predictions with the least amount of error among the tasted algorithm
- Unlike other models, linear regression model also performed very well but be careful R2 = 1.00 can sometimes indicate        overfitting or data leakage. 
- Random forest performed reasonably well good r2 score(0.98) but higher MAE and RMSE than GB model, so RF is acceptable but   not the best
- The LSTM model showed poor performance due to limited dataset size. Dataset contained only 121 row records, the model        could not effectively learn temporal patterns, resulting in a  negative R2 score

## Technology Used
- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
- Plotly
- Tensorflow
  
## Models Used
- Linear Regression
- Random Forest
- Gradient Boosting
- LSTM
