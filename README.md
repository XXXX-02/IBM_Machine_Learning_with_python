# IBM_Machine_Learning_with_python


This dataset is about past loans. The **Loan_train.csv** data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
| -------------- | ------------------------------------------------------------------------------------- |
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |

following algorithm are used to Train model:

*   K Nearest Neighbor(KNN)
*   Decision Tree
*   Support Vector Machine
*   Logistic Regression

also check loan_staus of new unknown data and check jaccobi_score, F1_score and logloss(apply on logistic Regression)

Result of our model:

| Algorithm          | Jaccard | F1-score | LogLoss |
| ------------------ | ------- | -------- | ------- |
| KNN                | 0.740741       | 0.700673       | NA             |
| Decision Tree      | 0.759259       | 0.761886       | NA             |
| SVM                | 0.740741       | 0.714431       | NA             |
| LogisticRegression | 0.740741       | 0.630418       | 0.483588       |        
