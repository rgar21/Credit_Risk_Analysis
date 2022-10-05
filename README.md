# Credit_Risk_Analysis

## Purpose

The intent of this analysis is to determine whether we should implement machine learning into our companies assessment of credit risk. Credit risk is an inherently unbalanced classification problem as the number of positive loans easily outnumber the negative ones. Therefore, we will use imbalanced-learn and scikit-learn libraries to create unbalanced classes to train our models. We will create and evaluate the below models to determine which one fits our needs the best:

  * RandomOverSampler
  * SMOTE
  * ClusterCentroids
  * SMOTEENN
  * BalancedRandomForestClassifier
  * EasyEnsembleClassifier

## Results

  * Random Oversampler
    * Balanced Accuracy Score: 0.657
    * Precision: 0.01
    * Recall: 0.71 
  
![Random_Oversampler](https://user-images.githubusercontent.com/106921601/194129916-f5d17ff6-6e7f-4b55-9dd0-78574af3c074.PNG)

 * SMOTE

![SMOTE](https://user-images.githubusercontent.com/106921601/194127993-f95c602a-68b5-4c9c-b3e4-c2beafb0525e.PNG)

 * ClusterCentroids

![ClusterCentroids](https://user-images.githubusercontent.com/106921601/194128016-e72e996d-1aec-4c9a-a430-74a98d2690b5.PNG)

 * SMOTEENN

![SMOTEENN](https://user-images.githubusercontent.com/106921601/194128028-5b78bd23-cf26-4615-a9f0-8b5127e934ac.PNG)

 * BalancedRandomForestClassifer

![BalancedRandonForestClassifier](https://user-images.githubusercontent.com/106921601/194128039-b7edd023-3b3f-411a-8e22-7512a5e749de.PNG)

 * EasyEnsembleClassifer

![EasyEnsembleClassifier](https://user-images.githubusercontent.com/106921601/194128062-cd269149-03bc-4a8c-93ef-046eeda63ad8.PNG)
