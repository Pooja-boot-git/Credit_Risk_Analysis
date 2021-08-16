# Overview of the analysis: 
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will evaluate a few supervised learning algorithms to predict credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

**1. Random Oversampling**

![image](https://user-images.githubusercontent.com/82654977/129498037-a8cac581-6095-46ec-8fce-d6177640211d.png)

**2.  SMOTE Oversampling**

![image](https://user-images.githubusercontent.com/82654977/129498090-2bc9309e-ab59-4ad6-943f-a8005ec9cd72.png)

**3. Cluster Centroids Undersampling**

![image](https://user-images.githubusercontent.com/82654977/129498165-95214d27-582e-4f80-897c-0548eac991fd.png)

**4. SMOTEENN Oversampling & Undersampling**

![image](https://user-images.githubusercontent.com/82654977/129498281-f4e479b0-cdac-41a8-aabc-b63757dbc357.png)

**5. Balanced Random Forest Classifier**

![image](https://user-images.githubusercontent.com/82654977/129498377-c17c5195-2931-41bd-8cdc-8ba9cce5f313.png)

**6. Easy Ensemble AdaBoost Classifier**

![image](https://user-images.githubusercontent.com/82654977/129498416-ee93e415-d7d1-42ae-8bcc-2d5896962fd0.png)

### Summary: 
Looking at the result set, we can safely say that Easy Ensemble Classifier is the best model to predict high risk credit cases. Precision score for high risk transaction is high






































