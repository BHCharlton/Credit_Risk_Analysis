# Credit_Risk_Analysis

## Overview of Analysis
There are several different tools and datasets available to help determine credit risk in the financial industry.  In this project, we used Python to build and evaluate several machine learning models to help in predicting this risk.  Here are some of the procedures that were used:
* Oversampling the data using the RandomOversampler and SMOTE algorithms
* Undersampling the data using the ClusterCentroids algorithm
* A combinatorial approach of over- and undersampling using the SMOTEENN
* Compare the classifiers BalancedRandomForestClassifier and EasyEnsembleClassifier, which help to reduce bias in machine learning

We will then evaluate the results of each algorithm to determine if they should be used to predict credit risk

## Algorithm Results

### Oversampling (RandomOversampler)
![Oversam](https://user-images.githubusercontent.com/93561592/164338304-2ed54905-a700-4f6e-beec-60df830c1b0f.PNG)

### Oversampling (SMOTE)
![SMOTE](https://user-images.githubusercontent.com/93561592/164338423-9069771c-40ce-429a-9536-bc64905c8b75.PNG)

### Undersampling (Cluster Centroids)
![Undersam](https://user-images.githubusercontent.com/93561592/164339796-d59fb73b-2e9c-4f56-9029-f67460ba03cd.PNG)

### Combination Sampling (SMOTEENN)
![Combosam](https://user-images.githubusercontent.com/93561592/164339993-f4066bb0-dcf2-4a90-be49-eb2bba4b2ff8.PNG)

