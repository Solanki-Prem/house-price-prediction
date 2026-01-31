# House Price Prediction using Linear Regression

## Project Overview
This project demonstrates an end-to-end machine learning workflow for predicting house prices using **Linear Regression**.  
The focus is on **clean EDA, visualization, and model evaluation** using a simple and beginner-friendly dataset.


## Dataset
- Source: Kaggle
- Rows: 1000
- Features: 7 numerical features
- Target Variable: `House_Price`

### Features
- Square_Footage
- Num_Bedrooms
- Num_Bathrooms
- Year_Built
- Lot_Size
- Garage_Size
- Neighborhood_Quality


## Exploratory Data Analysis
- No missing values
- All features are numerical
- Strong linear relationships with the target variable
- Scatter plots used to analyze feature impact


## Model Used
- **Linear Regression (scikit-learn)**

### Train-Test Split
- 80% Training
- 20% Testing


## Model Performance
| Metric | Value |
|------|------|
| R² Score | 0.9984 |
| RMSE | ~10,071 |

High accuracy due to clean and linear data distribution.


## Tech Stack
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn


##  How to Run
```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
