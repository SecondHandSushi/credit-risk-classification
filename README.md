Credit Risk Classification
Matthew Idle
University of Minnesota Data Analytics and Visualization Bootcamp
September 2023

Overview:
The purpose of this analysis is to determine the risk associated with a person's credit as it applies to getting a loan. Factors taken into consideration are the individual's loan size, interest rate, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model:

Accuracy: The accuracy is the true positives plus the true negatives divided by everything, both false and true. In our case, it is calculated as (18679 + 558) / (18679 + 558 + 80 + 67) = 19237 / 19384 = 0.99, which means we are very accurate with respect to our true positive and true negatives since we don't have many false values. Our high-performance model keeps it real.

Precision: Precision is the measure of the accuracy of the true positives, which is calculated as truePositives / (truePositives + falsePositives) = 18679 / (18679 + 80) = 0.99. This model has very high precision.
Recall: "measures the effectiveness of a classification model in identifying all relevant instances from a dataset", and is measured as the true positives divided by the true positives plus the false negatives. It is calculated as 18679 / (18679 + 67) = 18679 / 18746 = 0.996, which rounds up to 1.0.

Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning:

Given the low number of false values, both positive and negative, and the classification report showing excellent numbers, the model appears to be performing very well for the given data. However, the number of true positives to true negatives is a staggering 34:1, making it very imbalanced. So, I feel more data is required before any reasonable decision can be made. Otherwise, the bank could be in serious trouble, and if it's a big bank, it is going to cost the taxpayers a lot of money since the government would bail it out, but that is a whole different discussion. So, I would not recommend using this model unless a lot more data is provided.


References:
Géron, Aurélien. Hands-on Machine Learning with Scikit-Learn, Keras and Tensorflow: Concepts, Tools, and Techniques to Build Intelligent Systems. O’Reilly Media, 2019. 
 “Scikit-Learn.” Scikit, scikit-learn.org/stable/index.html. Accessed 21 Feb. 2024. 
 
Also used chat gpt for general questions and spell check