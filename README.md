# credit-risk-classification

This project challenge shows the analysis to evaluate the performance of customers creditworthiness by using machine learning algorithms to show the portential  of a loan borrower. The model is trained to identify factors that show the potential of loan approval and credit worthiness.

Model Criterias: 
1) Loan Size
2) Interest Rate
3) Borrowers Income
4) Debt to Income
5) Number of Accounts
6) Derogatory Marks
7) Total Debt

With the information above, Logistic Regeression Model is used to to fit data to predict if how likely a potential loan could go into default looking at 75036 customers. 

Model 1 - Logistic Regression
F1 score
Accuracy: .99
Healhty: 1.0
Unhealthy: .88
Weighted avg: .99

Model 2 - Logistic Regression with RandomOverSampler
F1 score
Accuracy: .99
Healhty: 1.0
Unhealthy: .92
Weighted avg: .99

Both models performed well where both F1 scores shows healthy loans. The difference shows in Model 2 where theres a slight jump in unhealthy loans by 0.04 which can be atrributed by oversampling model. 
Using the LogisticRegression with RandomoverSampler model would better fit this case as it showspotential of higher risk loans that would give better picture for creditors when issuing loans.
