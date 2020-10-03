### Telecom Churn Case Study

This project aims to predict whether a particular customer will switch to another telecom provider or not. In telecom terminology, 
this is referred to as churning and not churning, respectively.

### Model Used
Logistc Regression

### Libraries Used
Pandas, Numpy, sklearn, statsmodels, Matplotlib, Seaborn

### Methodology:
Step 1 Merged Churn data, Customer data and Churn data into a joint dataset
Step 2 Converted Categorical features into Numeric features using pandas dummy variable creation
Step 3 Standardized the features and Dropped Least Correlated features with target variable
Step 4 Feature Selection  done using RFE and features with high p-values and variance Inflation factors are dropped
Step 5 Model is created and using ROC curve, optimal Cutoff Point with balanced sensitivity and specificity
       is chosen to get the better prediction of Customer Churn Data 
       
### Conclusion:

Provided Telecom Industry a valuable insight into prediction of which customers are churning so that Telecom Industry can make strategic plans to retain those customers
      

 
 
