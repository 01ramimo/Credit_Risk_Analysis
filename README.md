# Credit_Risk_Analysis

### Overview

The purpose of this analysis is to help predict an individual’s low or high credit risk status by analyzing all the factors presented in the loan_stats data. Using supervised learning techniques (imbalanced-learn and scikit-learn libraries) to build models and evaluate them using a resampling method. The following were performed:

•	Using the randomoversample, SMOTE algorithms and undersampling the first couple of models data were oversampled with clustercentroid algorithm.

•	Whereas, in the remaining model a combination approach was used to over and undersample the data using smoteen.

•	Lastly, to minimize bias, balancedrandomforestclassifier and easyensembleclassifier two machine learning models were used for comparison.

### Results

•	Naive Random Oversampling Accuracy Score

![image](https://user-images.githubusercontent.com/89875689/152697940-5f976b31-cf49-40c8-aa5e-1a294ee5ded8.png)


• SMOTE oversampling results:

![image](https://user-images.githubusercontent.com/89875689/152698019-127c3e27-52a4-47e0-8068-15ac7b971e2f.png)


• Undersampling results:

![image](https://user-images.githubusercontent.com/89875689/152698067-87c62db7-2f51-4689-a6b0-20f8742948d8.png)


•	Combination (Over and Under) Sampling results

![image](https://user-images.githubusercontent.com/89875689/152698220-5c176f36-e381-483f-b363-4dc4e68c0ef9.png)
