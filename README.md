# Airbnb booking prediction  https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings

####EDA:
- EDA_initial: a quick look at all CSV files.

- EDA_MissingValue&Visualization: further exploratory data analysis: visualizing the data in various aspects



####Feature engineering: 
- Feature_engineering__session_Feature_extraction: new features are extracted from the raw data in the web session table

- Feature_engineering__main: feature decompostion, feature extraction, missing value imputatoin, one-hot encoding and feature scaling


####Feature selection:

- Feature_selection_RF__CLF_RF: feature selection using random forest, classification using random forest

- Feature_selection_L1norm: feature selection logistic regression regularized with L1 norm, classification using random forest


####Classfication:

- Classifier_RF: random forest classifier with k-fold cross validation

- Classification_RF_confusion_matrix: Checking the confusion matrix of the random forest classifier.

- Classification_RF_confusion_matrix_balanced_1: apply random  forest (with parameter class_weight = 'balanced')

- Classification_RF_confusion_matrix_balanced_2: apply random forest (with parameter class_weight = 'balanced') to the data set with binarized labels ('NDF' and 'non-NDF')

- Classification_RF_cutoff: apply Random forest with different cutoff value for prediction to the data set with binarized labels, ROC curve.


####Others:

- NDCG_score_func: NDCG scoring function, see https://www.kaggle.com/wiki/NormalizedDiscountedCumulativeGain for details
