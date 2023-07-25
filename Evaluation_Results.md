## ANALYZING PERFORMANCE

To pick a machine learning model out of a bunch of classifiers, we need to assess different performance parameters and the kind of data that we are working with. Performance of
the models have been evaluated on the following parameters:

1. ROC curve and AUC value – The ROC curve displays the TPR against the FPR at different threshold levels, separating the signal from the noise. The Area Under the Curve is used to measures the classifier's ability to distinguish between classes.
2. RMSE - The root-mean-square error is a metric used for comparing values predicted by a model or estimate to values observed.
3. F-1 score - F1 Score is the weighted average of Precision and Recall. It is frequently more valuable than accuracy, especially if the distribution of classes is unequal.
4. Misclassification Rate - The Misclassification Rate is a performance indicator that indicates the percentage of incorrect predictions.
5. AIC Score - The Akaike information criterion is a predictor of prediction error and thus relative model quality for a given set of data.
6. Matthews Correlation Coefficient - MCC is a quality indicator for binary classifications.


<img width="500" alt="Screenshot 2023-07-24 at 8 33 47 PM" src="https://github.com/shreyasbhat132/Predicting-Customer-Satisfaction---Olist-E-commerce-Dataset/assets/125607571/d9d16508-437e-47bf-a406-d50982f9135a">

## RESULTS

By comparing the performance parameters for all the models, it was a close competition between the Boosted Tree, the Random Forest Classifier, and the Neural Network Classification model. Since each model have their own advantages, boosted trees perform better with unbalanced data, which is what represents the Olist sales data. Since boosted tree also had a slightly better MCC score and AIC Score than the other models, we consider Boosted Tree Classifier to be the best fit model for customer satisfaction.

The selected model can be implemented in understanding -

1. Customer purchasing intent.
2. Product with highest sales potential.
3. Popular sellers based on quality of service.
4. Target Logistics Networks that would result in minimum freight prices and maximum satisfaction.
