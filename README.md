# Housing Regression Models

## 📌 Project Overview

This project focuses on implementing and evaluating regression models using the Housing dataset with Python and Scikit-learn.

The main objective is to compare three regression algorithms: Linear Regression, Ridge Regression, and Lasso Regression. Each model is trained and evaluated to understand its performance in predicting housing prices.

This project is part of my Machine Learning learning journey, where I am developing practical skills in regression algorithms, model training, and performance evaluation.

## 🎯 Objectives

- Load and explore the Housing dataset using Pandas.
- Separate input features and the target variable.
- Split the dataset into training and testing sets.
- Implement Linear Regression, Ridge Regression, and Lasso Regression.
- Train each model and generate predictions.
- Evaluate model performance using MSE, RMSE, R², and MAE.
- Compare the results of the three regression models.

## 📊 Dataset Information

This project uses the **Housing Dataset**, which contains information about housing characteristics and median house values.

### 🔗 Dataset Source

The dataset is loaded directly from the following URL:

[Housing Dataset – GitHub](https://raw.githubusercontent.com/jbrownlee/Datasets/master/housing.data)

- **Dataset Name:** Housing Dataset
- **Total Records:** 506
- **Input Features:** 13
- **Target Variable:** `MEDV`
- **Data Format:** Text file without column headers

### Dataset Features

The dataset contains the following 14 columns:

`CRIM`, `ZN`, `INDUS`, `CHAS`, `NOX`, `RM`, `AGE`, `DIS`, `RAD`, `TAX`, `PTRATIO`, `B`, `LSTAT`, `MEDV`.

The target variable `MEDV` represents the median value of owner-occupied homes.

## 🛠️ Tools and Technologies

- Python
- NumPy
- Pandas
- Scikit-learn
- Google Colab
- Jupyter Notebook
- GitHub

## 📁 Project Structure

```text
housing-regression-models/
│
├── README.md
├── .gitignore
├── requirements.txt
└── housing_regression_analysis.ipynb
```

## ⚙️ Analysis Workflow

### 1. Load the Dataset
- Import NumPy, Pandas, and Scikit-learn libraries.
- Load the Housing dataset directly from the provided URL.
- Assign column names because the dataset has no headers.
- Inspect the dataset using Pandas.

### 2. Split the Dataset
- Separate input features (`X`) and target variable (`y`).
- Use `train_test_split` to divide the dataset.
- Training data: 80%
- Testing data: 20%
- Random state: 42

### 3. Train Regression Models

Three regression algorithms are implemented:

**Linear Regression**
- A basic regression algorithm used to predict continuous values.

**Ridge Regression**
- Uses L2 regularization to reduce the impact of large model coefficients.
- Alpha: 1.0

**Lasso Regression**
- Uses L1 regularization to control model complexity.
- Alpha: 0.1

### 4. Evaluate Models

The models are evaluated using four regression metrics:

- **Mean Squared Error (MSE):** Measures the average squared prediction error.
- **Root Mean Squared Error (RMSE):** Measures prediction error in the target variable's scale.
- **R² Score:** Measures how much variation in the target variable is explained by the model.
- **Mean Absolute Error (MAE):** Measures the average absolute prediction error.

### 5. Compare Results

The evaluation results are organized into a comparison table to understand the performance of each model.

## 📈 Model Comparison Results

| Model | MSE | RMSE | R² | MAE |
|---|---:|---:|---:|---:|
| Linear Regression | 24.2911 | 4.9286 | 0.6688 | 3.1891 |
| Ridge Regression | 24.4772 | 4.9474 | 0.6662 | 3.1329 |
| Lasso Regression | 25.1556 | 5.0155 | 0.6570 | 3.1452 |

## 🔍 Key Findings

- Linear Regression achieved the lowest MSE and RMSE.
- Linear Regression achieved the highest R² score of 0.6688.
- Ridge Regression achieved the lowest MAE of 3.1329.
- Lasso Regression had a slightly lower R² score than the other two models.

Based on these results, Linear Regression performed best overall on this particular train-test split, while Ridge Regression achieved the lowest average absolute error.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Understanding regression algorithms.
- Loading and handling datasets using Pandas.
- Splitting datasets into training and testing sets.
- Implementing regularization techniques.
- Training and testing machine learning models.
- Evaluating regression model performance.
- Comparing multiple regression algorithms using evaluation metrics.

## 🚀 Future Improvements

- Apply feature scaling and preprocessing.
- Experiment with different regularization parameters.
- Perform cross-validation.
- Explore additional regression algorithms.
- Apply hyperparameter tuning to improve model performance.

- GitHub: [salmanfarsiali](https://github.com/salmanfarsiali)
- LinkedIn: [Salman Farsi](https://www.linkedin.com/in/salmanfarsiali/)
