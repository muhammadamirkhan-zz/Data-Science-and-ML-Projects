# Automatic-Machine-Learning-with-H2O-AutoML-and-Python
A project with introduction to H2O AutoML using Python. The objective is to predict whether or not a customer will enroll in a bank's term loan


This was a project on Automatic Machine Learning with H2O AutoML and Python. By doing this project, I am now able to describe what AutoML is and apply automatic machine learning to a business analytics problem with the H2O AutoML interface in Python. H2O's AutoML automates the process of training and tuning a large selection of models, allowing the user to focus on other aspects of the data science and machine learning pipelines such as data pre-processing, feature engineering, and model deployment.
I took a dataset of a bank to predict whether or not a customer will buy a bank product. I created a H2O cluster, converted the pandas data frame into h2oframe, and then split the data into train and test sets followed by training via h2o cluster by setting the training time to 10 minutes rather than one hour.
After training, I looked closely at the models and then further explored the best model which, in my case, was stack_ensemble. I also looked at the variable importance of most important base model.
Overall, it was an amazing experience since it was my first time I explored AutoML.
