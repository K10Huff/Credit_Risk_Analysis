# Credit Risk Analysis

# Overview of the Analysis
 The purpose of this analysis was to compare and contrast the different machine learning techniques  abilities to correctly predict risky loan applications.

# Results 
- Naive Random Oversampling 
    - Balanced Accuracy Score: 0.645, Precision Score: 0.99, Recall Score: 0.61, f1 Score: 0.68 <br>
![Naive Random Oversampling ](https://github.com/K10Huff/Credit_Risk_Analysis/blob/0926c02aea02e3ab7db282bb39e784c0f886dddc/Images/01%20Naive%20Random%20Oversampling.png)

- SMOTE Oversampling 
    -	Balanced Accuracy Score: 0.64, Precision Score: 0.99, Recall Score: 0.66, f1 Score: 0.79 <br>
![SMOTE Oversampling](https://github.com/K10Huff/Credit_Risk_Analysis/blob/0926c02aea02e3ab7db282bb39e784c0f886dddc/Images/02%20SMOTE%20Oversampling.png)

- Undersampling 
    -	Balanced Accuracy Score: 0.52, Precision Score: 0.99, Recall Score: 0.45, f1 Score: 0.62 <br>
![Undersampling](https://github.com/K10Huff/Credit_Risk_Analysis/blob/0926c02aea02e3ab7db282bb39e784c0f886dddc/Images/03%20Undersampling.png)

- Combination Sampling 
    -	Balanced Accuracy Score: 0.64, Precision Score: 0.99, Recall Score: 0.58, f1 Score: 0.73 <br>
![Combination Sampling](https://github.com/K10Huff/Credit_Risk_Analysis/blob/0926c02aea02e3ab7db282bb39e784c0f886dddc/Images/04%20Combination%20Sampling.png)

- Balanced Random Forest Classifier
    -	Balanced Accuracy Score: 0.715, Precision Score: 0.99, Recall Score: 0.84, f1 Score: 0.91 <br>
![Balanced Random Forest Classifier](https://github.com/K10Huff/Credit_Risk_Analysis/blob/0926c02aea02e3ab7db282bb39e784c0f886dddc/Images/05%20Balanced%20Random%20Forest%20Classifier.png)

- AdaBoost Classifier
    -	Balanced Accuracy Score: 0.63, Precision Score: 0.99, Recall Score: 1.00, f1 Score: 0.99 <br>
![AdaBoost Classifier](https://github.com/K10Huff/Credit_Risk_Analysis/blob/0926c02aea02e3ab7db282bb39e784c0f886dddc/Images/06%20AdaBoost%20Classifier.png)

# Summary
Based on the classification metrics I would suggest using the AdaBoost Classifier. All of the models performed well on the precision metric (the values classified as positive, were indeed all actually positive.) The differences ocurred in the models' Recall/ Sensitivity (the model’s ability to correctly identify all of the positive values within the dataset. In the AdaBoost classifier all of the positive values were identified. In this instance, identifying the risk to the company is more financially important than erring on the side of caution and mistakenly labeling someone a risk when they are not.
