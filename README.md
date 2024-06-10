# Titanic Survival Prediction Analysis

This project aims to analyze the Titanic dataset and predict survival outcomes using machine learning models. The dataset contains information about passengers aboard the Titanic, including their demographic details and whether they survived or not.

## Dataset

The dataset used in this project is sourced from the Titanic-Dataset.csv file. It includes the following features:

- Passenger class (Pclass)
- Sex
- Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Fare
- Embarked port

## Exploratory Data Analysis (EDA)

The analysis explores various factors influencing survival rates, such as passenger class, gender, age, and embarkation port. Visualizations, including heatmaps and bar plots, are used to understand the relationships between different features and survival probabilities.

## Preprocessing and Model Building

Data preprocessing techniques, such as handling missing values and encoding categorical variables, are applied. Two machine learning models are trained: logistic regression and support vector classifier (SVC). These models are evaluated based on their accuracy in predicting survival outcomes.

## Results

- Logistic Regression: achieved an accuracy of approximately 79.85%.
- Support Vector Classifier: achieved an accuracy of approximately 81.34%.

## Usage

To run the analysis and predict survival outcomes:

1. Clone the repository.
2. Ensure you have Python installed along with necessary libraries (pandas, numpy, seaborn, scikit-learn).
3. Run the Titanic_Survival_Prediction.ipynb Jupyter Notebook.
4. Analyze the EDA findings and model predictions.

## Conclusion

The project demonstrates the application of machine learning techniques in predicting survival probabilities based on passenger data. By understanding the factors influencing survival rates, we can gain insights into historical events such as the Titanic disaster.
