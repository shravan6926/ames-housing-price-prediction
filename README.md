# Ames Housing Price Prediction

A Machine Learning project that predicts residential house prices using property features from the Ames Housing dataset.

The project explores data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction using different regression algorithms.

## Project Overview

The main objective is to build a regression model that can estimate the sale price of a house based on features such as:

- Overall quality of the house
- Living area
- Year built
- Garage capacity
- Basement area
- Number of rooms
- Other property characteristics

## Dataset

This project uses the Ames Housing dataset from the Kaggle competition:

**House Prices: Advanced Regression Techniques**

Dataset: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

The dataset contains:
- `train.csv` – Training data with house features and sale prices.
- `test.csv` – Test data without sale prices.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook / Google Colab

## Project Structure

```text
ames-housing-price-prediction/
│
├── dataset/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── house_prices_prediction.ipynb
│
├── reports/
│   └── project_report.pdf
│
├── screenshots/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Handling Missing Values
5. Categorical Feature Encoding
6. Feature Engineering
7. Target Variable Transformation using Log Transformation
8. Model Training
9. Model Comparison and Hyperparameter Tuning
10. Model Evaluation
11. Error and Outlier Analysis
12. Final Predictions

## Machine Learning Models

The following regression algorithms were explored:

- Linear Regression
- Linear Regression with Log Transformation
- Ridge Regression
- Random Forest Regressor
- Tuned Random Forest Regressor
- Gradient Boosting Regressor

## Best Model Performance

The best validation result in the experiments was obtained using Linear Regression with a log-transformed target, trained after investigating unusual observations.

| Metric | Validation Result |
|---|---:|
| MAE | $15,214.19 |
| RMSE | $23,150.51 |
| R² Score | 0.9301 |

These results are from the project's validation experiment and should not be interpreted as a Kaggle leaderboard score.

## Installation and Usage

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project folder

```bash
cd ames-housing-price-prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Alternatively, open the notebook using Google Colab.

## Project Report

The detailed project report is available in the `reports/` directory.

## Future Improvements

- Experiment with advanced ensemble models.
- Improve feature engineering.
- Perform additional hyperparameter optimization.
- Deploy the trained model as a web application.
- Improve prediction performance on unseen data.

## Acknowledgements

- Kaggle – Ames Housing dataset.
- Scikit-learn documentation.
- Python data science community.

---