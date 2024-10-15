# Sure_Tomorrow_Insurance_Benefits_Predictions
The Sure Tomorrow company needs a machine learning model that can predict whether or not a customer is likely to receive an insurance benefit.

- Task 1: Find customers who are similar to a given customer. This will help the company's agents with marketing.
- Task 2: Predict whether a new customer is likely to receive an insurance benefit. Can a trained prediction model do better than an untrained dummy model? Can it do worse? Explain your logic.
- Task 3: Predict the number of insurance benefits a new customer is likely to receive using a linear regression model.
- Task 4: Protect clients' personal data without breaking the model from the previous task.


## Data Description

`/datasets/insurance_us.csv`
- Features: insured person's gender, age, salary, and number of family members.
- Target: number of insurance benefits received by an insured person over the last five years.

## Conclusion:

- The dataset had no missing values or null values. The mean and median ages are the same but income is skewed negatively. Columns for gender and insurance benefits are binary values.

- The distance between points is affected by distance calculations using manhattan and euclidean distance.

- Data scaling is effected when using kNN because it prioritizes large numbers over smaller values.

- Increasing k had no effect on F1 score.

- Using the class LinearRegression model, we had an RMSE of .34 and R2 = .66

- Obfuscating Data and Using Linear Regression proved results are the same whether we scaled or used the data
