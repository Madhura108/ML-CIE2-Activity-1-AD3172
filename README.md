# Machine Learning CIE 2 - Titanic Dataset

## Student Information

- Activity: Machine Learning CIE 2
- Domain: Transport
- Dataset: Titanic Dataset
- Roll Number: AD3172

## About the Activity

This project was completed as part of the Machine Learning CIE 2 activity.

The objective of this activity was to select, inspect, clean, analyse, encode and scale a tabular dataset and prepare it for potential future machine learning use.

## Dataset

The Titanic dataset was selected from the Transport domain.

The dataset contains information about passengers who travelled on the RMS Titanic, including passenger class, name, gender, age, family members travelling together, ticket information, fare, cabin information and port of embarkation.

### Dataset Source

Kaggle Titanic Dataset:
https://www.kaggle.com/code/chanchal24/titanic-dataset/input?select=train.csv

#Work Completed

The following activities were performed:

1. Selected and loaded the Titanic dataset.
2. Inspected the first and last records.
3. Checked dataset shape, column names and data types.
4. Identified numerical and categorical columns.
5. Calculated summary statistics.
6. Identified `Survived` as a potential future prediction target.
7. Checked missing values and calculated their percentages.
8. Handled missing values using appropriate methods.
9. Removed the `Cabin` column because of its high percentage of missing values.
10. Checked for duplicate records.
11. Checked categorical values for inconsistencies.
12. Performed exploratory data analysis.
13. Created suitable visualisations.
14. Applied one-hot encoding to nominal categorical variables.
15. Standardised appropriate numerical features using `StandardScaler`.
16. Performed final data-quality checks.
17. Saved the prepared dataset as `titanic_prepared.csv`.

## Key Results

- The original dataset contained 891 rows and 12 columns.
- Missing values were found in `Age`, `Cabin` and `Embarked`.
- `Age` missing values were replaced using the median.
- `Embarked` missing values were replaced using the mode.
- `Cabin` was removed because approximately 77% of its values were missing.
- No unwanted duplicate records were found.
- `Sex` and `Embarked` were encoded using one-hot encoding.
- `Age`, `SibSp`, `Parch` and `Fare` were standardised using `StandardScaler`.
- `PassengerId` was not scaled because it is an identifier.
- `Survived` was not scaled because it is the potential target variable.
- The final prepared dataset contains 891 rows and 12 columns.
- The final prepared dataset contains no missing values or duplicate rows.

# Files

| File | Description |
|---|---|
| `ML_Activity-1.ipynb` | Completed Jupyter Notebook containing the complete activity |
| `titanic_prepared.csv` | Final prepared Titanic dataset |
| `README.md` | Project description and results |

# Conclusion

The Titanic dataset was successfully cleaned and prepared for potential future machine learning analysis. Missing values were handled using suitable techniques, categorical features were encoded, and selected numerical features were standardised. Duplicate and consistency checks were also performed. The final prepared dataset was saved separately so that the original dataset remained unchanged.

#Faculty Reference and Acknowledgement

Faculty profile:

https://github.com/Princy2129

This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources:
https://github.com/Princy2129
