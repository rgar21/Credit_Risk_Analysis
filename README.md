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

![RandomOverSampler](https://user-images.githubusercontent.com/106921601/194139551-19f550f9-25e7-4bb1-b438-b3f5ccb22cf1.PNG)

  * SMOTE
    * Balanced Accuracy Score: 0.657
    * Precision: 0.01
    * Recall: 0.71  

![SMOTE](https://user-images.githubusercontent.com/106921601/194127993-f95c602a-68b5-4c9c-b3e4-c2beafb0525e.PNG)

  * ClusterCentroids
    * Balanced Accuracy Score: 0.545
    * Precision: 0.01
    * Recall: 0.69
  
![ClusterCentroids](https://user-images.githubusercontent.com/106921601/194128016-e72e996d-1aec-4c9a-a430-74a98d2690b5.PNG)

  * SMOTEENN
    * Balanced Accuracy Score: 0.657
    * Precision: 0.01
    * Recall: 0.71 
 
![SMOTEENN](https://user-images.githubusercontent.com/106921601/194128028-5b78bd23-cf26-4615-a9f0-8b5127e934ac.PNG)

  * BalancedRandomForestClassifer
    * Balanced Accuracy Score: 0.788
    * Precision: 0.04
    * Recall: 0.67

![BalancedRandonForestClassifier](https://user-images.githubusercontent.com/106921601/194128039-b7edd023-3b3f-411a-8e22-7512a5e749de.PNG)

 * EasyEnsembleClassifer
    * Balanced Accuracy Score: 0.925
    * Precision: 0.07
    * Recall: 0.91

![EasyEnsembleClassifier](https://user-images.githubusercontent.com/106921601/194128062-cd269149-03bc-4a8c-93ef-046eeda63ad8.PNG)

## Summary

Based on the results of our models we can say that all but one of these models will not work for our purposes. Across the board the precision score for each model is not satisfactory to our needs. Our low precision scores are indicative of a large number of false positives. When we look at the recall value we see a similar story; as all but one model hover around .70. This tells us that our model will yield a large number of false negatives. However, there is one model that stood out amongst all the inaccurate ones, and that is the Easy Ensemble Classifier. While our precision score is not as high as we would like it to be, the recall value of .91 is easily the highest amongst our tested models. Therefore, I would recommend that we move forward with the Easy Ensemble Classifier and find a way to improve its precision score.


