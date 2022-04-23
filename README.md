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

The balanced accuracy score comes to 62.5%

The high-risk precision is approximately 1% with a sensitivity of 60% resulting in an F1 of only 2%

Due to the high number of the low-risk population, the precision is close to 100% with a sensitivity of 65% resulting in a much higher F1 of 79%

### Oversampling (SMOTE)
![SMOTE](https://user-images.githubusercontent.com/93561592/164338423-9069771c-40ce-429a-9536-bc64905c8b75.PNG)

The resutls for SMOTE are similar to RandmOversampler

The balanced accuracy score comes to 65.1%

The high-risk precision is approximately 1% again with a sensitivity of 64%, also resulting in an F1 of only 2%.

Once again, the high number of the low-risk population results in a precision that is close to 100% with a sensitivity of 66% resulting in a much higher F1 of 79%.

### Undersampling (Cluster Centroids)
![Undersam](https://user-images.githubusercontent.com/93561592/164339796-d59fb73b-2e9c-4f56-9029-f67460ba03cd.PNG)

The balanced accuracy score drops to 51.6% when undersampling

The high-risk precision is approximately 1% with a sensitivity of 60% resulting in an F1 of only 1%

Due to the high number of false positives, the low-risk sensitivity is only 43% despite a precision close to 100%


### Combination Sampling (SMOTEENN)
![Combosam](https://user-images.githubusercontent.com/93561592/164339993-f4066bb0-dcf2-4a90-be49-eb2bba4b2ff8.PNG)

The balanced accuracy score is somewhat higher at 61.3% when using combination sampling

The high-risk precision is approximately 1% with a sensitivity of 69% resulting in an F1 of 2%

Similar to undersampling, the high number of false positives results in a low-risk sensitivity of only 43% despite a precision close to 100%


### Balanced Random Forest Classifier
![Forest](https://user-images.githubusercontent.com/93561592/164586935-065ef77e-e0ff-416a-9964-1474d3449821.PNG)

The balanced accuracy score has now risen to 78.8%

The high-risk precision is higher at 4% with a sensitivity of 67% resulting in an F1 of 7%

Due to the lower number of false positives, the low-risk sensitivity in now 91% with a precision close to 100% again


### Easy Ensemble AdaBoost Classifier
![Adaboost](https://user-images.githubusercontent.com/93561592/164588180-7265a3a6-c9d6-4820-b8e2-50204050a36f.PNG)

The balanced accuracy score is now at its best, coming in at 92.5%

The high-risk precision is approximately 7% with a sensitivity of 91% resulting in an F1 of 14%

Due to the lower number of false positives, the low-risk sensitivity is now even higher at 94% with a precision close to 100% again

## Summary
words go hear
