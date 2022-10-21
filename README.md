# Housing-Price-Regression
This project utilizes housing features to develop a regression model for predicting housing prices.

The Regressors utilized for this project are;

1. Decision Tree Regressor.
2. Linear Regression.
3. Random Forest Regressor.
4. KNeighbours Regressor.
5. Regression with RFECV using Decision Tree Regressor, Extra Tree Regressor, and AdaBoost Regressor.

Data Preprocessing was done by visualizations, cleaning, imputting missing values, and scaling in some cases, to minimize outlier effects.

Categorical encoding of type Onehot and Ordinal was also used.

Techniques applied for feature selection and dimensionality reduction on some of the regressors include:

1. SelectKBest.
2. Principal Component Analysis (PCA).
3. Recursive Feature Elimination with Cross-Validation.
4. SelectFromModel.
5. Truncated Single Value Decomposition (TruncatedSVD).
6. VarianceThreshold.

Different pipelines were created to handle categorical and numerical features, and finally, the grid search cross validation iterator was used to ensure our model predicts without overfitting.

The results on accuracy based on the R-square score is as presented in the table below:

![image](https://user-images.githubusercontent.com/103940202/197244665-bbe4e225-db7d-4636-aecf-c68a6cf3ecc7.png)
