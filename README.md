# Task_titanic
## Summary:

### Data Analysis Key Findings

* The dataset contains missing values in the 'Age', 'Cabin', and 'Embarked' columns, with 'Cabin' having a substantial number of missing entries.
* Missing values in 'Age' were imputed with the median, and missing values in 'Embarked' were imputed with the mode. The 'Cabin' column was dropped due to a high number of missing values.
* Categorical features ('Sex' and 'Embarked') were successfully one-hot encoded, creating new numerical columns and removing the original categorical columns.
* Numerical features ('Pclass', 'Age', 'SibSp', 'Parch', and 'Fare') were scaled using `StandardScaler`, transforming their values to have a mean of approximately 0 and a standard deviation of 1.
* Box plots indicated the presence of significant outliers in the 'SibSp', 'Parch', and 'Fare' columns.
