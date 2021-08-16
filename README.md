# Overview of the analysis: 
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will evaluate a few supervised learning algorithms to predict credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

## Results: 

**1. Random Oversampling**

Overall accuracy score is close to 64%. When we dig deeper, classification report tells us that sesitivity for high risk transaction as well as precision is not great for this model.

![image](https://user-images.githubusercontent.com/82654977/129498037-a8cac581-6095-46ec-8fce-d6177640211d.png)

**2.  SMOTE Oversampling**

SMOTE oversampling isn't giving us very good results either. Our f1 score is very low given low recall and precisions for high risk credits.

![image](https://user-images.githubusercontent.com/82654977/129498090-2bc9309e-ab59-4ad6-943f-a8005ec9cd72.png)

**3. Cluster Centroids Undersampling**

This model gives us very low recall as well as precision for high risk transactions.

![image](https://user-images.githubusercontent.com/82654977/129498165-95214d27-582e-4f80-897c-0548eac991fd.png)

**4. SMOTEENN Oversampling & Undersampling**

This model's sensitivity towards high risk credits is a little better than other models but precision is still very low.

![image](https://user-images.githubusercontent.com/82654977/129498281-f4e479b0-cdac-41a8-aabc-b63757dbc357.png)

**5. Balanced Random Forest Classifier**

We see a slight increase in precision but sensitivity is still very low for high risk credits.

![image](https://user-images.githubusercontent.com/82654977/129498377-c17c5195-2931-41bd-8cdc-8ba9cce5f313.png)

**6. Easy Ensemble AdaBoost Classifier**

This model is by far giving us the best recall towards high risk credits. There is a little increase in precision as well for high risk credits.

![image](https://user-images.githubusercontent.com/82654977/129512632-3131a7c0-5314-4445-ab22-b46f9415bf65.png)


### Summary: 
Although we have high sensitivity(recall) in our models for High Risk transactions but precision is very low hence we see a drop in F1 score. However, in comparision to all the algorithms, Easy Ensemble Classifier gave the best precision and highest recall for high risk credits. Easy Ensemble Classifier is very good if the requirement is to be more sensitive towards high risk transactions.






































