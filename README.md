# Benchmark_Top_ML_Algorithms

Used different ML algorithms to solve a specific problem.

### Dataset
Predict Loan Eligibility for Dream Housing Finance company

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.

Train: https://raw.githubusercontent.com/subashgandyer/datasets/main/loan_train.csv

Test: https://raw.githubusercontent.com/subashgandyer/datasets/main/loan_test.csv

### Models

- Decision Tree
- KNN
- Logistic Regression
- SVM
- Random Forest
- Gaussian Naive Bayes

---
### Steps

1. Preprocess Raw Dataset
2. Import Models
3. GridSearchCV for finding the best model with the best hyperparameters
4. Best Accuracy
5. Verify the data loading function can reproduce previous results
6. Created code to get prediction on test.csv
