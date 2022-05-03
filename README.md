# Credit Risk Analysis

# Overview of the Analysis
 The purpose of this analysis was to compare and contrast the different machine learning techniques  abilities to correctly predict risky loan applications.

# Results 
- Naive Random Oversampling 
    - Balanced Accuracy Score: 0.645, Precision Score: 0.99, Recall Score: 0.61, f1 Score: 0.68 <br>
![Naive Random Oversampling ](link)

- SMOTE Oversampling 
    -	Balanced Accuracy Score: 0.64, Precision Score: 0.99, Recall Score: 0.66, f1 Score: 0.79 <br>
![SMOTE Oversampling](link)

- Undersampling 
    -	Balanced Accuracy Score: 0.52, Precision Score: 0.99, Recall Score: 0.45, f1 Score: 0.62 <br>
![Undersampling](link)

- Combination Sampling 
    -	Balanced Accuracy Score: 0.64, Precision Score: 0.99, Recall Score: 0.58, f1 Score: 0.73 <br>
![Combination Sampling](link)

- Balanced Random Forest Classifier
    -	Balanced Accuracy Score: 0.715, Precision Score: 0.99, Recall Score: 0.84, f1 Score: 0.91 <br>
![Balanced Random Forest Classifier](link)

- AdaBoost Classifier
    -	Balanced Accuracy Score: 0.63, Precision Score: 0.99, Recall Score: 1.00, f1 Score: 0.99 <br>
![AdaBoost Classifier](link)

# Summary
Based on the classification metrics I would suggest using the AdaBoost Classifier. All of the models performed well on the precision metric (the values classified as positive, were indeed all actually positive.) The differences ocurred in the models' Recall/ Sensitivity (the model’s ability to correctly identify all of the positive values within the dataset. In the AdaBoost classifier all of the positive values were identified. In this instance, identifying the risk to the company is more financially important than erring on the side of caution and mistakenly labeling someone a risk when they are not.
