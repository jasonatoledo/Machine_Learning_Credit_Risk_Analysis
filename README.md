# Machine_Learning_Credit_Risk_Analysis


## Overview

The purpose of this challenge was to apply machine learning to solve a real-world problem, credit risk. Because the number of good loans is so unbalanced compared to the number of bad loans, it is a challenge dealing with an unbalanced dataset. The dataset contained a lot of features to help build a model that can hopefully predict high-risk accounts more easily. In this challenge, I went through 6 different models/techniques of supervised machine learning in order to arrive at a conclusion.




## Results

The results for the 6 tests were varied as I went through each one. To describe the results further:

- Naive Random Oversampling: Accuracy Score: 0.64  Pre: 0.01    Rec: 0.72
https://github.com/jasonatoledo/Machine_Learning_Credit_Risk_Analysis/blob/main/Naive%20Random%20Oversampling.png

- SMOTE Oversample: Accuracy Score: 0.65  Pre: 0.01    Rec: 0.61
https://github.com/jasonatoledo/Machine_Learning_Credit_Risk_Analysis/blob/main/SMOTE.png

- Undersampling Cluster Centroids: Accuracy Score: 0.54  Pre: 0.01   Rec: 0.67
https://github.com/jasonatoledo/Machine_Learning_Credit_Risk_Analysis/blob/main/ClusterCentoids.png

- Combination Over/Under SMOTEEN: Accuracy Score: 0.64  Pre: 0.01    Rec: 0.72
https://github.com/jasonatoledo/Machine_Learning_Credit_Risk_Analysis/blob/main/SMOTEEN.png

- Balanced Random Forest Classifier: Accuracy Score: 0.69  Pre: 0.88    Rec: 0.38
https://github.com/jasonatoledo/Machine_Learning_Credit_Risk_Analysis/blob/main/random_forest_results.png

- Easy Ensemble Adaboost Classifier: Accuracy Score: 0.64  Pre: .33    Rec: 0.01
https://github.com/jasonatoledo/Machine_Learning_Credit_Risk_Analysis/blob/main/adaboost.png



## Summary

It was very interesting to use the different models with the dataset and see the results. If I had to choose a model as the best choice, I would go with the Naive Random Oversampling model as it had the best recall for predicting high risk accounts. SMOTEEN would be the 2nd choice as it produced similar results but to be honest, I would probably need to do a lot more tuning or try other models to make a better informed choice. Random forest had the best precision but poor recall. I couldn't make a solid recommendation at this point in time based off what I've seen and would like to try more modeling.
