# Credit default risk
Credit default risk is the risk that a lender takes the chance that a borrower fails to make required payments of the loan.

In the Jupyter Notebook file [credit-risk-prediction.ipynb](https://github.com/alilajevardi/Risk-Modelling/blob/main/credit-risk-prediction.ipynb), KNN, logistic regression, decision tree, random forest and XGBoost have been exploited to find the best predicitve algorithms. Further, RandomizedSearchCV and GridSearchCV were implemented for hyperparamters-tuning.

# Exploratory Data Analysis (EDA)
Dataset tablular:
![Dataset table](https://github.com/alilajevardi/Risk-Modelling/blob/main/artifacts/01_tabular.png)

Dataset info:
``` text
RangeIndex: 32581 entries, 0 to 32580
Data columns (total 12 columns):
 #   Column                      Non-Null Count  Dtype  
---  ------                      --------------  -----  
 0   person_age                  32581 non-null  int64  
 1   person_income               32581 non-null  int64  
 2   person_home_ownership       32581 non-null  object 
 3   person_emp_length           31686 non-null  float64
 4   loan_intent                 32581 non-null  object 
 5   loan_grade                  32581 non-null  object 
 6   loan_amnt                   32581 non-null  int64  
 7   loan_int_rate               29465 non-null  float64
 8   loan_status                 32581 non-null  int64  
 9   loan_percent_income         32581 non-null  float64
 10  cb_person_default_on_file   32581 non-null  object 
 11  cb_person_cred_hist_length  32581 non-null  int64  
dtypes: float64(3), int64(5), object(4)
memory usage: 3.0+ MB
```

NaN precentage in dataset:
``` text
person_age                    0.00
person_income                 0.00
person_home_ownership         0.00
person_emp_length             2.75
loan_intent                   0.00
loan_grade                    0.00
loan_amnt                     0.00
loan_int_rate                 9.56
loan_status                   0.00
loan_percent_income           0.00
cb_person_default_on_file     0.00
cb_person_cred_hist_length    0.00
dtype: float64
```
## Obeservation

- Only two columns of data contains NaN

- person_emp_length contains 2.75% NaN and loan_int_rate contains 9.56% NaN


