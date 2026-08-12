# Mobile Price Range Classification

## Project Overview

This project focuses on predicting the price range of mobile phones using Machine Learning classification techniques.

The objective is to classify mobile phones into different price ranges based on their technical specifications and features.

The project demonstrates an end-to-end Machine Learning workflow including data understanding, exploratory data analysis, preprocessing, model building, evaluation, and feature importance analysis.

## Objective

The main objective of this project is to predict the price range of a mobile phone based on its features.

The target variable contains four price categories:

- 0 - Low Cost
- 1 - Medium Cost
- 2 - High Cost
- 3 - Very High Cost

## Dataset

The dataset contains information about mobile phone specifications and features such as:

- Battery power
- Bluetooth
- Clock speed
- Dual SIM
- Front camera
- Internal memory
- Mobile depth
- Mobile weight
- Number of cores
- Primary camera
- Pixel resolution
- RAM
- Screen height
- Screen width
- Talk time
- Touch screen
- 3G
- 4G
- WiFi
- Price range

The target variable is `price_range`.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading

The mobile phone dataset was loaded using Pandas and inspected to understand its structure.

### 2. Basic Data Checks

Initial checks were performed to understand:

- Number of rows and columns
- Data types
- Missing values
- Duplicate records
- Statistical summary

The dataset was checked to ensure data quality before applying Machine Learning models.

### 3. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the distribution of the target variable and the relationships between mobile phone features and price range.

The analysis included:

- Target variable distribution
- Numerical feature distributions
- Feature relationships
- Correlation analysis

### 4. Data Preprocessing

The dataset was prepared for Machine Learning by:

- Separating features and target variable
- Checking data quality
- Splitting the dataset into training and testing sets
- Applying feature scaling where required

### 5. Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

### 6. Model Evaluation

The models were evaluated using classification accuracy and confusion matrix.

The Logistic Regression model performed particularly well after feature scaling.

## Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 97.5% |
| Decision Tree | 82% |
| Random Forest | 90.5% |

The Logistic Regression model achieved the best performance with approximately **97.5% accuracy**.

## Confusion Matrix

The confusion matrix for the final classification model was:

| | Predicted 0 | Predicted 1 | Predicted 2 | Predicted 3 |
|---|---:|---:|---:|---:|
| Actual 0 | 101 | 4 | 0 | 0 |
| Actual 1 | 0 | 91 | 0 | 0 |
| Actual 2 | 0 | 2 | 87 | 3 |
| Actual 3 | 0 | 0 | 1 | 111 |

The confusion matrix shows that the model correctly classified the majority of mobile phones into their respective price ranges.

## Feature Importance

Feature importance analysis was performed to understand which mobile phone specifications contributed most to price range prediction.

Among the important features, **RAM** was identified as one of the most influential features for predicting mobile phone price range.

## Key Findings

- Mobile phone specifications can be used effectively to predict price categories.
- Logistic Regression achieved the highest accuracy among the evaluated models.
- Feature scaling improved the performance of Logistic Regression.
- RAM was an important feature for price range prediction.
- The model achieved approximately 97.5% accuracy on the test data.

## Conclusion

This project demonstrates how Machine Learning classification techniques can be used to predict mobile phone price ranges based on technical specifications.

After comparing multiple classification models, Logistic Regression achieved the best performance with approximately 97.5% accuracy.

The project provides an end-to-end example of applying Machine Learning to a real-world classification problem.

## Future Improvements

The project can be further improved by:

- Hyperparameter tuning
- Cross-validation
- Trying additional classification algorithms
- Feature selection
- Model deployment using Flask or FastAPI
- Creating a user interface for price range prediction

## Author

**Bhavani K.**
