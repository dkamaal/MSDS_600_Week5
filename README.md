# Week 5-Assignment

## MSDS 600 - Introduction to Data Science

## Data Science Automation

## Professor: Dr. Aiman Gannous

### Prepared By: Danish Kamaal

---

## Summary

First updated `TotalCharges_tenure_ratio` Column name to `charge_per_tenure` in `prepped_Churn_data.csv` file to match with column name in `new_churn_data.csv` file to make predictions. Then loaded data from `prepped_Churn_data.csv` file using pandas. Then installed `pycaret` package, also installed compatible `scikit-learn` version that supports `PyCaret`. PyCaret is used for AutoML and compares different machine learning models. Data type of `Contract` , `PaymentMethod` and `PhoneService` was Categorical, so updated it to numeric, also set preprocess to False for getting xgboost and lightgbm working. On comparing models `Logistic Regression` turned out to be best model. 

Next step is to Save and Load the best model. Used pickle module to save data in Binary format, file is saved as pickle file. `load_model` function was used to load saved best model which is `Logistic Regression` to make prediction. `VS Code` IDE was used to create Python file. Loaded `new_churn_data.csv` in to data frame and pycaret best model was used to get prediction. On making prediction, we had one false negative. So basically best moded performed fairly well, though it is not perfect.

Also downloaded GitHub GUI Desktop application as I already had GitHub Account logged in and created repository `MSDS_600_Week5`. [Link to Week 5 Assignment GitHub Repository](https://github.com/dkamaal/MSDS_600_Week5)
