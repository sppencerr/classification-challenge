# Spam Email Classification Challenge

This project builds and compares two machine learning models to detect spam emails using a labeled dataset. The models used are:

- **Logistic Regression**
- **Random Forest Classifier**

## Dataset

The dataset contains 57 numerical features representing word/character frequency and email formatting patterns. The target label (`spam`) indicates whether an email is spam (`1`) or not (`0`).

## Workflow

1. Imported and explored the dataset.
2. Split the data into training and testing sets.
3. Scaled the features using `StandardScaler`.
4. Trained and evaluated both models.
5. Compared model performance using accuracy scores.

## Conclusion

The Random Forest model performed better than the Logistic Regression model, confirming our hypothesis that an ensemble method would better capture the complexity of spam classification.

## Tools Used

- Python (Pandas, scikit-learn)
- Jupyter Notebook