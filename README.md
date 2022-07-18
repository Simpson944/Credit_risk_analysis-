# Credit_risk_analysis
### The puropose of the analysis is to evaluate loan out comes and the factors that drive those outcomes by utilizing differnt methods of machine learning. We will look at various machine learning methods and evaluate performace based on multiple measurments such as accuracy and percision

## Results: 
- Naive Random OverSampling
    
    - This method was more balanced at 65%
    - Precision score .99
    - Recall score .63

- SMOTE OverSampling 

    - Balance score of 64%
    - Precision score .99 
    - Recall score .67

- Undersampling ClusterCentroids 

    - Balance score of 54%
    - Precision score of .99
    - Recall score .42

- Combination SMOTEENN

    - Balance of 54%
    - Precision score .99
    - Recall score .57

- Random Forest 

    - Balance of 100%
    - Precision score 1
    - Recall score 1

- Easy Ensemble Adaboost Classifier 

    - Balance of 100%
    - Precision score 1
    - Recall score 1 

----
## Summary 
### The best model ran was the combination under / over sampling. It had the least amount of instances of predicting a good outcome that actually resulted in a bad outcome at 26 instances (a .15% failure rate). And incorrect prediction of a bad loan outcome is not preferred over a model incorecctly predicting a bad outcome. 