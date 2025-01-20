## Short Comings of the Paper
- no hyperparameter selection

## My Improvement
- KNN Imputer only on train data
- Get feature importance from Random Forest and spearman correlation to detect the 5 most important features
- Randomforest with Gridsearch with all features and 5 features
- KNN Classifier on all features and 5 features; Gridsearch with 5 features (due to better performance)
- Support Vector Machine Classifier on all features and 5 features; Gridsearch with 5 features (due to better performance)


## Unimplemented Ideas 
- removing outliers was not done due to lack of expertise of medicine background
- set different threshold
- no feature engineering due to lack of new information