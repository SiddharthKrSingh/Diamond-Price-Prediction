# DIAMOND PRICE PREDICTION
# 1.PROJECT OVERVIEW
This project aims to develop a machine learning model capable of predicting diamond prices. This can be a valuable tool for various stakeholders in the diamond industry, including appraisers, buyers, and sellers. The model will be trained on a dataset containing diamond characteristics and their corresponding selling prices.

By leveraging machine learning algorithms, we can analyze the complex relationships between these features (carat weight, cut, color, clarity, etc.) and predict prices more accurately than traditional methods that rely solely on human expertise.

# 2. DATA ACQUISITION
This dataSet is taken from Kaggle link -> https://www.kaggle.com/datasets/shubhankitsirvaiya06/diamond-price-prediction
The EDA has been performed on the dataSet, techniques such as->
a. Simple Imputer-> which handles missing Values.
b. One Hot Encoding-> which is used to transform categorical features into numerical features by asssigning ranks to the it.

# 3. MACHINE LEARNING AND MODEL EVALUATION
We have trained the the data on various models which are used for Regression such as LINEAR REGRESSION, LASSO REGRESSION, ELASTICNET REGRESSION, DECISION TREE among which DICISION TREE gives the best best result in when we evaluated the model using R2_SCORE

# 4. PIPELINING 
We have build the training_pipeline and the test_pipeline to automate the process

# 5. ADDITION INFORMATION
flask is used to run the server

# 7. TECHNOLOGY USED
 a. python
 b. pandas 
 c. numpy
 d. flask
 e.skit-learn
