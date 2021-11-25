https://medium.com/jbennetcodes/how-to-rewrite-your-sql-queries-in-pandas-and-more-149d341fc53e

Main steps of training a ML algorithm:
- Pre-process the data:
    - Numerical values: Replace NaN values by Median or Mean (imputer)
                        Normalize the data (StandardScaler())
    - Categorical values: One Hot Encoding (OneHotEncoder)

- Apply the algorithm:
    - Regression: Baseline: Linear Regression
                Better: Random Forest Regressor
        Metric: Mean Squared Error
    - Classification: Baseline: Logistic Regression (if binary classification)
                    Better: Random Forest Classifier
        Metric: F1 score

- Apply Cross Validation to spot possible overfitting

- Apply Grid Search for finetuning of the parameters

- Make predictions