# CreditRiskAnalysis

The German Credit Card dataset is analyzed and validated and predictive models are trained on this data to attempt and assist in anticipating a 
customer’s credit worthiness for loan approval based on parameters presented in the data such as age, marital status, employment, assets, 
occupation, dependents and so on. 

The goal for the models is to provide overall high accuracy with emphasis on a low rate of False Positives to minimize risky credits. 

A measure defined as ‘Risk’, which tracks False Positive rate was added to assist with model selection. 

Decision Tree and Naïve  Bayes classification algorithms were trained using a 70/30 split strategy as well as with dataset with a subset of attributes and results compared. Algorithm accuracy varied between 62% and 70%, with Decision Tree showing the best results. 

The main factor that increased the ‘Risk’ measure significantly was the exclusion of too many features regardless of the modelling algorithm. 
However, including the top 50% of highly correlated attributes showed comparable results to using all attributes. 

The unbalanced nature of the dataset reflected in the poor detection rate of negatives, resulting in ~ 72% precision for predicting Good Credit but only about 59% for predicting Bad Credit. 

The main recommendation would be to work on either balancing the dataset or collecting additional data in order to improve the model so that Bad Credit can be predicted with higher precision.

The tools that will be used is mainly Pandas, Numpy, Matplotlib and Sickit Learn packages in Python for data investigation, visualization, developing and comparing supervised learning algorithms. 
