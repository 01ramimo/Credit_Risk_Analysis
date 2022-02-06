# Credit_Risk_Analysis

### Overview

The purpose of this analysis is to help predict an individual’s low or high credit risk status by analyzing all the factors presented in the loan_stats data. Using supervised learning techniques (imbalanced-learn and scikit-learn libraries) to build models and evaluate them using a resampling method. The following were performed:

•	Using the randomoversample, SMOTE algorithms and undersampling the first couple of models data were oversampled with clustercentroid algorithm.

•	Whereas, in the remaining model a combination approach was used to over and undersample the data using smoteen.

•	Lastly, to minimize bias, balancedrandomforestclassifier and easyensembleclassifier two machine learning models were used for comparison.

### Results

### •	Naive Random Oversampling Accuracy Score - balanced accuracy test is 65%

![image](https://user-images.githubusercontent.com/89875689/152698335-a8bf8bef-25ce-4016-b00d-7bebf37a14ca.png)

### • SMOTE oversampling results - accuracy score is 66%

![image](https://user-images.githubusercontent.com/89875689/152698399-b26266f1-e1e3-4344-acf1-2a9bc7faad46.png)

### • Undersampling results - balanced accuracy score is 54%

![image](https://user-images.githubusercontent.com/89875689/152698442-10894589-873b-41d1-9d4e-d24ac4c896ba.png)

### •	Combination (Over and Under) Sampling results - balanced accuracy score is 64%

![image](https://user-images.githubusercontent.com/89875689/152698477-dbbbb218-d2ee-4e85-a8af-e141ee72ebb2.png)

### • Balanced Random Forest Classified - accuracy score is 77%

![image](https://user-images.githubusercontent.com/89875689/152698878-6b4f5f7c-bd36-4973-a103-071969d0fe2a.png)

### • Easy Ensemble AdaBoost Classified - accuracy score is 92%

![image](https://user-images.githubusercontent.com/89875689/152698993-ab54f6a2-f655-4147-b10d-d9c95b9f7e7d.png)


### Summary




