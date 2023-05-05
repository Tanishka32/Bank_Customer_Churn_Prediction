# Bank_Customer_Churn_Prediction

![Car](https://dezyre.gumlet.io/images/blog/churn-models/Customer_Churn_Prediction_Models_in_Machine_Learning.png)

# Objective

The following are the goals and objectives: analyse and list the elements or features that influence client churn. Build and hone a machine learning model to anticipate potential churn and aid customer service. address the potential churn-causing elements to stop client turnover and reduce loss of revenue.

# Data description

+ **RowNumber** — the record (row) number and has no effect on the output.

+ **CustomerId** — contains random values and has no effect on customer leaving the bank.

+ **Surname** — the surname of a customer has no impact on their decision to leave the bank.

+ **CreditScore** — can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank. Geography- a customer’s             location can affect their decision to leave the bank.

+ **Gender** — it’s interesting to explore whether gender plays a role in a customer leaving the bank. We’ll include this column, too.

+ **Age** — this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

+ **Tenure** — refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.

+ **Balance** — also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those         with lower balances.

+ **NumOfProducts** — refers to the number of products that a customer has purchased through the bank.

+ **HasCrCard** — denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.     (0=No,1=Yes)

+ **IsActiveMember** — active customers are less likely to leave the bank, so we’ll keep this. (0=No,1=Yes)
 
+ **EstimatedSalary** — as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

+ **Exited** — whether or not the customer left the bank. This is what we have to predict. (0=No,1=Yes)
