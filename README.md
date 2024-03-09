## Supervised Classification of Heart Disease Tabular Data using the KNN,SVM,decision tree and random forest. 

- After some EDA to understand the data, data preprocessing is done by handling outliers and the categorical data. 
- Handled outliers by imputing zero-valued missing value only with its median. 
- Handle categorical data with one-hot encoding as the label is nominal. 

- Train all models with train set. Additionaly, I apply feature scaling to the data before employing distance-based algorithms like KNN and SVM to ensure that all features contribute equally to the model by bringing them to a common scale. To prove this, conducted experiment on the dataset with and without feature scaling for SVM and KNN, shows a significant increase in performance for the dataset with feature scaling. Without scaling, features with larger magnitudes might dominate the calculation, leading the model to be biased towards those particular features. 

- Evaluate model performance with Classification Report,Confusion Matrix,Roc Curve,and Precision Recall Curve

- The accuracy of these 4 models are compared among each other. SVM resulted to be the best model with 88% testing accuracy.
