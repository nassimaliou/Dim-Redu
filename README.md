# Dim-Redu
Dimensionality reduction refers to techniques that reduce the number of input variables in a dataset, these techniques can be used in applied machine learning to simplify a classification or regression dataset in order to better fit a predictive model.
There are 5 jupiter notebooks in this repo :

- corr.ipynb : Removing strongly correlated features through the calculation of pairwise correlation
- t-sne.ipynb : Feature selection after fitting a "t-distributed stochastic neighbor embedding" visualization of high-dimensional data
- var.ipynb : Filtering out low variance features using a VarianceThreshold feature selector.
- TB_lasso.ipynb : Recursive Feature Elimination with random forests (wraping a Recursive Feature Eliminator around a random forest model to remove features step by step) + training and fitting a Lasso model on the dataset, calculating its R² score and then selecting features to be ignored based on the model results.
- pca.ipynb : Probably the most frequently used dimensionality reduction algorithm, Principal Component Analysis, a feature extraction technique used for data exploration, data pre-processing and compression.
