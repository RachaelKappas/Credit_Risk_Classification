# Credit_Risk_Classification
Module 20 Challenge


# Overview of the Analysis
The purpose of this analysis is to evaluate the effectiveness of a logistic regression model in predicting credit risk. Specifically, we aim to classify loan applications into two categories: healthy loans (label 0) and high-risk loans (label 1). The analysis focuses on assessing the model’s accuracy, precision, and recall to determine its reliability and suitability for making informed credit decisions.

# Results
*Accuracy Score:
99% - The model correctly predicted the loan status 99% of the time, demonstrating high overall performance.

*Precision Score:
Healthy Loans (0): 1.00 - The model has perfect precision for predicting healthy loans, meaning it rarely misclassifies healthy loans as high-risk.
High-Risk Loans (1): 0.85 - The precision for high-risk loans is slightly lower, indicating some false positives where healthy loans are incorrectly identified as high-risk.

*Recall Score:
Healthy Loans (0): 0.99 - The model has a high recall for healthy loans, successfully identifying nearly all healthy loans.
High-Risk Loans (1): 0.91 - The recall for high-risk loans is high, meaning the model effectively identifies most high-risk loans, though there are a few false negatives.

#Summary
The logistic regression model demonstrates robust performance in predicting credit risk, particularly in identifying healthy loans with near-perfect precision and recall. For high-risk loans, the model is also effective but with a slight trade-off between precision and recall.



I used the assistance of ChatGPT to help understand the code I was creating. I also created this using google colab
