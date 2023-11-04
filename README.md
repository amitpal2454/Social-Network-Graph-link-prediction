# Social-Network-Graph-link-prediction

social network link prediction datasets are essential resources for researchers and data scientists working on predictive modeling tasks within social networks. 
Several datasets are commonly used for link prediction tasks, including:

Facebook Dataset: This dataset includes information about users, their connections, and various social interactions on the Facebook platform. 
It is often used for studying social network dynamics and for predicting links between users.
 I have used various ML algo to predict connection between users .
XGBoost perform better than random forest classifier as specified in reference document
follow back is most import features in the model
As our problem statement required not to miss any connection so we are getting high recall for test data.
i used 3 hyperparameter for XGB as estimitor,depth and learninng rate and they are perfectly tuned for best result
In the newly added assignment features preferntial Attachment Followee is most useful feature as compair to PA followers and svd_dot
