# Comparing-Custom-Model-Development-with-GCP-BQML-and-AutoML-Tables
Comparing Custom Model Development on Python Jupyter notebook with Google Cloud Platform BigQuery Machine Learning and AutoML Tables (beta)

Background:


I always had a curiosity about the Automatic Machine Learning on cloud platforms - 

1. Can they build faster, accurate and better models than I, as a data scientist or Machine Learning Engineer, can ever build? 

2. Are they transparent and explainable with respect to the transformations applied, the algorithms used or the optimal hyper-parameters chosen? 

3. Is it a tool that I can rely on? Or is it a competitor, a threat to me as a data scientist or ML engineer?   

4. Are they a replacement for Data Scientists / ML Engineers? Or just a quick enabler for Business Analysts? 

I wanted to try out these tools myself, and find out when we should use custom machine learning models and when to depend on cloud based automatic machine learning. 




Experiment Set Up: 

I selected a tiny dataset to start with - 
Data Source: https://archive.ics.uci.edu/ml/machine-learning-databases/concrete/compressive/

Track 1: Manual Exploratory Data Analysis in Python Notebook on my local machine and built multiple custom models after the typical steps like domain analysis, feature engineering and tuning. 

Track 2: Google Cloud Platform’s BigQuery ML to build Machine Learning model using SQL, with linear regressor and boosted tree regressor. 

Track 3: Using Google Cloud Platform’s AutoML Tables (beta) to see what sort of results it offers. 

Finally, after explaining all the steps in each track, I have included the Model performance parameters, conclusions and takeaways for when to use which approach. 




Detailed article on Medium: 



