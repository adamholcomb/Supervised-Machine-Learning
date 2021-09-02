# Supervised Machine Learning



Create an unsupervised machine learning  model to evaluate loan risk.  Scikitlearn library is used in python jupyter lab to create the model.



First used Logistic Regression and Random Forest models with unscaled data. Logistic Regression resulted in a poor score of 0.6485, while Random Forests resulted in an almost perfect score of 0.9999. I believe this is due to the high dimensionality of the dataset. This lends itself favorably to the decision tree based format of Random Forests and poorly to Logistic Regression.



Scaling the data resulted in a higher but still poor score for Logistic Regression of 0.7131. The Random Forest score remained unchanged, because it is based on decision trees, which do not rely on distance between points.



I believe using PCA to reduce the number of features would help the Logistic Regression model.