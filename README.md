# A Logistic Regression Approach To Identifying High-Risk Loan Applicants.
- Every step is well documented in the jupyter notebook.

## Objective 
To develop a predictive model for credit risk assessment using logistic regression by analyzing borrower financial and demographic data, 
to identify whether a loan applicant is likely to default on their loan to support more informed lending decisions and minimize financial
losses associated with credit defaults.

## Methodology 
1. Import relevant modules
2. Load and preview the dataset (credit_risk_dataset.csv file). The dataset was downloaded from Kaggle.
3. Check the shape of the dataset, inconsinstencies and datatype of the dataset.
4. Perform data cleaning and preprocessing - drop rows with missing columns, encode categorical columns so that they can be used in to create
5. a classification regression model.
6. Identify the dependent (target) and independent (predictors/features) variables.
7. Split the data into training and test set using a 75:25 (75% training and 25% test data) split.
8. Scale the data using standardization and fit only on training data & transform both (train and test data).
9.  Create a logistic regression model using training data and make predictions on test data.
10. Evaluate the model performance using a confusion matrix and Compute the model accuracy, precision, recall and f1_score using sciki-learn.
11. Lastly, interprete the model performance using the confusing matrix results.

### Tools & Libraries
Python 3.x                          - Programming language
NumPy                               - for mathematical computation
Pandas                              - for data manipulation and analysis
Scikit-learn                        - for splitting datasets, training the Logistic Regression model, evaluating performance (accuracy, precision, etc.)
                                    and preprocessing (scaling features).
Matplotlib / Seaborn                - for Exploratory Data Analysis (EDA) and for visualization.
Jupyter Notebook (optional)         - An interactive environment to write and run Python code. 

