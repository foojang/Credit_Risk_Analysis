**Overview**

Jill has asked us to use our machine learning skills to evaluate credit risk. We will be using credit card data from LendingClub a peer-to-peer lending company. We will use RandomOverSampler, SMOTE, SMOTEENN, BalancedRandomForestClassifier, EasyEnsembleClassifier to predict credit risk 

**Results**

RandomOverSampler
•	Balanced accuracy score is 62.49%
•	Precision for high risk is 1% and a recall of 60%
•	Precision for low risk in 100% and a recall of 65%

![image](https://user-images.githubusercontent.com/95973377/164570378-d02f2218-7ec3-4f3d-883a-598e11e2026d.png)

SMOTE 
•	Balanced accuracy score is 65.12%
•	Precision for high risk is 1% and a recall of 64%
•	Precision for low risk in 100% and a recall of 66%

![image](https://user-images.githubusercontent.com/95973377/164570428-6ce04877-95d2-413f-8909-3e505a3cc772.png)

Undersampling
•	Balanced accuracy score is 51.86%
•	Precision for high risk is 1% and a recall of 57%
•	Precision for low risk in 100% and a recall of 46%

![image](https://user-images.githubusercontent.com/95973377/164570469-db01b122-59e6-470e-b29c-51114d286804.png)

SMOTEENN

•	Balanced accuracy score is 61.64%
•	Precision for high risk is 1% and a recall of 69%
•	Precision for low risk in 100% and a recall of 54%

![image](https://user-images.githubusercontent.com/95973377/164570488-12d361fd-28ce-4eb3-bd6f-0f48785eea3c.png)

BalancedRandomForestClassifier

•	Balanced accuracy score is 78.77%
•	Precision for high risk is 4% and a recall of 67%
•	Precision for low risk in 100% and a recall of 91%

![image](https://user-images.githubusercontent.com/95973377/164570508-201a7834-1ccb-4e27-8c63-e3d277f9d43c.png)

EasyEnsembleClassifier

•	Balanced accuracy score is 92.54%
•	Precision for high risk is 7% and a recall of 91%
•	Precision for low risk in 100% and a recall of 94%

![image](https://user-images.githubusercontent.com/95973377/164570522-cbe8d1a6-3a99-4c11-91f2-fb546a4915e9.png)

**Summary**

I would recommend using EasyEnsembleClassifier. With a balanced accuracy score of 92% the machine learning can be the most accurate when truly detecting high and low risk burrowers. 
