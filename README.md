In this project, we analyze the data from a song application to predict the churn from users. The dataset (128 MB) we use here is a subset of the whole data. We use the power of apache spark to perform data manipulations and build our models for this problem.

Churn is defined as Submit Downgrade or Cancellation Confirmation events. If a user has at some instance performed the above two activities, he is considered a churned user.

We calculate the following metrics on which we build our models.

Number of Songs  
Number of sessions  
Churn  
Number of artists  

Random Forest Classifier performs the best on the dataset provided which provides a F1 score of 0.7069  

The blog post about the details of the findings can be found at Medium Post - https://medium.com/@ravi.tm1989/predicting-churn-with-spark-ea9579ad886d

Libraries used:

pySpark  
Pandas  
Seaborn  
Matplotlib  
