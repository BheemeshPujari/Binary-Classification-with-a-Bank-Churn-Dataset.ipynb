# Binary-Classification-with-a-Bank-Churn-Dataset.ipynb
Task is to predict whether a customer continues with their account or closes it (e.g., churns).We need to predict the probability of Exited.
## About the Data Set
1.Customer ID: A unique identifier for each customer  
2.Surname: The customer's surname or last name  
3.Credit Score: A numerical value representing the customer's credit score  
4.Geography: The country where the customer resides (France, Spain or Germany)  
5.Gender: The customer's gender (Male or Female)  
6.Age: The customer's age.  
7.Tenure: The number of years the customer has been with the bank  
8.Balance: The customer's account balance  
9.NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)  
10.HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)  
11.IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)  
12.EstimatedSalary: The estimated salary of the customer  
13.Exited: Whether the customer has churned (1 = yes, 0 = no)  

## Evaluation Metric
Evaluation is done based on the area under the ROC curve between the predicted probability and the observed target.
