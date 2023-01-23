# Bank-Customer-Churn-Prediction

Problem Setting:
Customer churn, also known as customer attrition, is the phenomenon in which a customer
leaves an organization. This customer attrition is likely to influence a bank's income for various
reasons, including service, facilities, and assistance provided to consumers. When compared to
client retention, the expense of marketing to gain new consumers is prohibitively expensive.
Problem Definition:
To grow a bank's business model, it is necessary to forecast the likelihood of client attrition. This
project's primary goal is to create a supervised machine-learning model that will help in the
classification of churn consumers.

Data Source:
The data was obtained from the well-known open-source repository Kaggle.
URL: https://www.kaggle.com/datasets/santoshd3/bank-customers

Data Description:
Its a bank customer data. The data consists of 10000 Customers across the globe. This data has the following columns:
No Feature Name
1.RowNumber,
2.CustomerId,
3.Surname,
4.CreditScore,
5.Geography,
6.Gender,
7.Age,
8.Tenure,
9.Balance,
10.NumOfProducts,
11.HasCrCard,
12.IsActiveMember,
13.EstimatedSalary,
14.Exited.

Please refer further data exploration, data visualization, label encoding, dimension reduction, data partioning, implementation of supervised ML models like Logistic rgeression, KNN, Random Forest Classifier, Perfomance evaluation from the attached report, code and slides. 

Overal Model Result:
The primary goal of this project was to identify the churning of a customer. The recall and
precision matrices are used to evaluate this accuracy. The Random Forest Classifier has the
highest accuracy of all three models (86.61%), followed by K Nearest Neighbour and Logistic
Regression. The K Nearest Neighbour algorithm has the highest precision for churned customers,
but the Random Forest Classifier has the highest recall value. There is still scope for increasing
the accuracy of the model by more than 90%.
