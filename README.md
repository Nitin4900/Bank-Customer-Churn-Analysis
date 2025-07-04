# Bank Customer Churn Prediction

This project uses machine learning to predict whether a customer is likely to churn (i.e., leave the bank) based on their profile and transaction behavior

---
## Techniques Used

- **Label Encoding** – for converting the `Gender` column into binary values
- **One-Hot Encoding** – applied on the `Geography` column to handle categorical data
- **Feature Selection** – selected relevant features such as:
  - `CreditScore`, `Gender`, `Age`, `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`, `Geography_Germany`, `Geography_Spain`
- **Feature Scaling** – standardized the feature set using `StandardScaler`
- **Train/Test Split** – 80% training and 20% testing using `train_test_split`

---

## Models Trained

- `RandomForestClassifier`
- `LogisticRegression`
- `SVC` (Support Vector Machine)
- `KNeighborsClassifier`
- `GradientBoostingClassifier`

---
