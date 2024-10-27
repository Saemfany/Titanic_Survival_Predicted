# Predicting Survival - Titanic Dataset Analysis 🚢

This repository contains an analysis of the famous Titanic dataset, focusing on predicting survival based on passenger features such as age, fare, class, and more. The goal of this project is to understand which factors were most influential in determining survival rates and to evaluate model performance using Decision Tree and Random Forest classifiers.

## Project Overview 📊

In this project, I analyze the Titanic dataset to predict passenger survival based on various characteristics. Using exploratory data analysis, feature engineering, and machine learning models, I gain insights into the factors affecting survival rates and assess model performance.

## Key Features of the Dataset 🧳

The Titanic dataset includes the following key features:

- **Passenger Information**: Age, Gender, Class, and Fare
- **Location Information**: Port of Embarkation
- **Family Information**: Number of siblings/spouses and parents/children aboard
- **Target Variable**: Survival status (1 for survived, 0 for did not survive)

## Project Objectives 🎯

1. **Data Exploration**: Identify patterns in the data related to survival.
2. **Feature Engineering**: Transform features such as family size and fare categorization for model improvement.
3. **Model Selection and Comparison**: Use Decision Tree and Random Forest models to predict survival and compare their performance.
4. **Feature Importance**: Determine which factors are most influential in predicting survival.

## Analysis Summary 📝

The analysis includes:

1. **Exploratory Data Analysis**:
   - Visualizations and summary statistics for understanding survival patterns.
   - Insights on feature relationships, such as the impact of age, fare, and class on survival.

2. **Model Building and Evaluation**:
   - **Decision Tree**: Provides a simple, interpretable model for predicting survival.
   - **Random Forest**: An ensemble method that improves accuracy by reducing variance.
   - **Evaluation Metrics**: Accuracy, Precision, Recall, and F1-score for both models, with a final model comparison.

3. **Feature Importance**:
   - Highlights the most influential features based on each model, helping to interpret model predictions and assess factor impact on survival.

## Repository Contents 📂

- **Data**: [train.csv](https://github.com/Saemfany/Titanic_Survival_Predicted/blob/bcfac8e872221b18c46c2d2ab0444a9c27354c37/train.csv) - The dataset used for analysis.
- **Code**: [Titanic_Survival_Predicted.ipynb](https://github.com/Saemfany/Titanic_Survival_Predicted/blob/bcfac8e872221b18c46c2d2ab0444a9c27354c37/Titanic_Survival_Predicted.ipynb) - Jupyter notebook with code for data cleaning, EDA, model building, and evaluation.
- **Reports**: [Titanic.pdf](https://github.com/Saemfany/Titanic_Survival_Predicted/blob/bcfac8e872221b18c46c2d2ab0444a9c27354c37/Titanic.pdf) - Slide report with key insights and visualizations.
- **README.md**: Overview and guide to this repository.

## Results and Insights 📈

- **Random Forest** achieved a higher accuracy of 83% compared to Decision Tree, which had 78%.
- The most important features in predicting survival were **Fare** and **Sex** in both models.
- The analysis provides insights into the impact of passenger class, age, and family size on survival rates.

## Acknowledgements 🙏

- Dataset provided by [Kaggle](https://www.kaggle.com/competitions/titanic/).
- Thank you to mentors and resources that supported this project.

## Contact

For any questions or feedback, please feel free to reach out via email or connect on [LinkedIn](https://www.linkedin.com/in/syamsulrizalfany/).
