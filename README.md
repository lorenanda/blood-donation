# Predicting the churn rate of bank customers

In this project I explore a dataset from Kaggle to predict the churn rate of bank customers, using Logistic Regression and Random Forest Classifiers.

### Findings from exploratory data analysis:
- The average credit score of bank customers is 650, and it ranges from 350 to 850. However, the values below 370 are outliers.
- Customers who left the bank have a slightly lower credit score (646) than those who stayed (653).
- The average age of customers is 38 years old, and it ranges from 18 years to 92 years. Of these, the median age of the customers who left the bank is 45 years old, nine years olderd than the customers who stayed. 
- There are more male customers than female. From the customers who left the bank, most are female.
- Most customers are based in France, followed by Germany and Spain. Germany has the highest churn rate.
- Customers who left the bank have a higher balance and salary than those who stayed.
- The median tenure of the customers in both groups is 5 years.
- Customers who left the bank have less products (1) than those who stayed (2).

### Classification results:
- Logistic Regression: 83% accuray, 63% precision.
- Random Forest Classifier: 86.1% accuray, 75.1% precision.
