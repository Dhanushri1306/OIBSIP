# House Price Prediction

Oasis Infobyte Data Analytics Internship – Level 2

## Project Overview

This project focuses on predicting house sale prices using machine learning regression algorithms. The dataset is explored, preprocessed, and used to train and evaluate multiple models to identify the best-performing algorithm.

## Technologies Used

- Python 3.11
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Exploratory Data Analysis (EDA)
2. Missing Value Analysis
3. Feature Selection and Preprocessing
4. Categorical Feature Encoding
5. Training and Validation Split
6. Regression Model Training
7. Model Evaluation and Comparison
8. Final Prediction Generation

## Machine Learning Models

- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression

## Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Gradient Boosting | 17,194.50 | 27,544.77 | 0.9011 |
| Random Forest | 17,788.78 | 29,150.85 | 0.8892 |
| Linear Regression | 20,420.50 | 31,128.52 | 0.8737 |
| Decision Tree | 27,495.27 | 41,850.75 | 0.7717 |

Gradient Boosting achieved the best validation performance with an R² score of 0.9011.

## Project Files

- `HousePricePrediction.ipynb` – Complete analysis, preprocessing, model training, and evaluation.
- `dataset/` – Training and testing datasets.
- `submission.csv` – Final predicted house prices for the test dataset.

## Final Outcome

The Gradient Boosting model was selected and retrained using the complete training dataset. It generated 1,459 house price predictions, which were exported to `submission.csv`.
