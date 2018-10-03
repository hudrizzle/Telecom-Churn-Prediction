# Telecom-Churn-Prediction
**Results**:
Please check out the jupyter notebook of the project [here](https://github.com/hudrizzle/Telecom-Churn-Prediction/blob/master/Supervised%20Learning%20Project-Xiaoyu-1003.ipynb). If you experience loading problems (as it is a big file), please take a look of a markdown copy of the project [here](https://github.com/hudrizzle/User_Churn_Predictions/blob/master/results/User_Churn_Prediction.md)

**Keywords**:
4 supervised learning models - ensemble modeling - learning curves and confusion matrices -  ROC curve and PR curve - feature importance - 

**Description**:
In this project, I used supervised learning models to identify cell phone service customers who are more likely to stop using the service in the future and created a model that can predict if a certain customer will drop the service. Furthermore, I analyzed top factors that influence user retention to help the company prevent user churn.The dataset contains the information of customers' plans and usage of the service, as well as whether or not they stopped using the service eventually. 
- Data Source: https://www.sgi.com/tech/mlc/db/churn.all  
- Data info: https://www.sgi.com/tech/mlc/db/churn.names

I evaluated 4 popular classifiers using 4 different datasets and compared their performance using a stratified K-fold cross validation procedure. I examined the learning curves and confusion matrices of different classifiers and I found that the Random Forest has a AUROC score of 0.91 and better generalizes the prediction without over-fitting the training data. 

Furthermore, I derived the feature importance from logistic regression and random forest classifiers and I noticed that these two classifiers have different top features according to the relative importance. It means that their predictions are not based on the same features. Nevertheless, they share some common important features for the classification, e.g., day/night call charges. 

