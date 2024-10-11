# Heart-Attack-Risk-Prediction-using-ML
This project utilizes machine learning models to predict heart attack risk based on health and lifestyle factors like age, cholesterol, exercise habits, and more. Various classification algorithms, including Random Forest, Logistic Regression, and Gradient Boosting, were applied, and their performances were compared based on accuracy and precision.

## Project Overview

Heart disease is one of the leading causes of death globally. This project aims to help predict heart attack risk in individuals by leveraging machine learning models trained on a dataset of key health indicators and habits. The focus is on identifying high-risk patients based on data analysis and classification models.

### Key Features:
- Preprocessing of raw data, including handling of missing values and imbalanced datasets.
- Exploratory Data Analysis (EDA) to visualize and analyze important factors.
- Feature selection using Recursive Feature Elimination (RFE).
- Application of multiple machine learning models to compare accuracy, precision, and other performance metrics.

## Data Description

The dataset used in this project contains the following features:

- **Age**
- **Cholesterol**
- **Heart Rate**
- **Blood Pressure**
- **Diabetes**
- **Family History**
- **Smoking**
- **Obesity**
- **Exercise Hours Per Week**
- **Diet**
- **Alcohol Consumption**
- **Previous Heart Problems**
- **Stress Level**
- **Sedentary Hours Per Day**
- **BMI**
- **Triglycerides**
- **Physical Activity Days Per Week**
- **Sleep Hours Per Day**
- **Heart Attack Risk** (Target Variable: 0 = Low Risk, 1 = High Risk)

## Models Applied

The following classification models were used in this project:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Decision Tree**
4. **Support Vector Classifier (SVC)**
5. **KNeighbors Classifier**
6. **Gaussian Naive Bayes**
7. **Gradient Boosting**

### Model Performance Summary

| Model                   | Accuracy | Precision |
|-------------------------|----------|-----------|
| Logistic Regression      | 0.4982   | 0.5005    |
| Random Forest            | 0.7876   | 0.8446    |
| Decision Tree            | 0.7129   | 0.6817    |
| SVC                      | 0.5649   | 0.5650    |
| KNeighbors Classifier     | 0.5764   | 0.5744    |
| Gaussian NB              | 0.4893   | 0.4906    |
| Gradient Boosting        | 0.5622   | 0.5655    |

### Best Performing Model

- The **Random Forest Classifier** performed the best with an accuracy of **78.76%** and precision of **84.46%**.


## Key Steps in the Project

1. **Data Preprocessing**:
    - Handled missing data, performed feature scaling using `MinMaxScaler`, and balanced the dataset using `RandomOverSampler`.

2. **Exploratory Data Analysis (EDA)**:
    - Visualized correlations and examined the distribution of key health indicators.
    - Created heatmaps and other visualizations to understand relationships between variables.

3. **Feature Selection**:
    - Applied Recursive Feature Elimination (RFE) to select the most relevant features for the prediction task.

4. **Modeling**:
    - Compared multiple machine learning models.
    - Performed hyperparameter tuning using GridSearchCV for optimal results.

5. **Model Evaluation**:
    - Evaluated models based on Accuracy, Precision, Recall, F1-score, and ROC-AUC.

## Conclusion

- **Random Forest Classifier** was identified as the most effective model for predicting heart attack risk, offering high accuracy and precision.
- Further improvements could be made by incorporating more advanced models like XGBoost or by experimenting with feature engineering and tuning.

## Future Enhancements

- Adding more features or additional datasets.
- Experimenting with advanced algorithms like XGBoost or LightGBM.
- Improving feature engineering techniques for better accuracy.

## License

This project is licensed under the MIT License. Feel free to modify or contribute!

---

Feel free to customize the content as needed before uploading to GitHub!
