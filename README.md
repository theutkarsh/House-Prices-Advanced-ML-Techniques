# House-Prices-Advanced-ML-Techniques 

The code is used to predict House_Prices with 79 explanatory variables describing (almost) every aspect of residential home. 
## Setup
scikit learn,numpy,pandas, keras, Xgboost

## File descriptions

* Keras tenserflow for house pricing.ipynb - Used Keras Neural Net to train model.
* Xgboost for House Prediction.ipynb- Used Xgboost algorithm to train model.
* ensemble house pricing.ipynb - Used ensemble of xgboost and lasso classifier to predict labels.
* lasso for house pricing.ipynb - Lasso regress used to predict labels.

### all/
* train.csv - the training set
* test.csv - the test set
* data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
* sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

### Submission/
Predicted labels on test set based on differnt models.

## Results

* ensemb_xglas.csv -ensemble model- 0.11834
* keras1.csv- tenserflow -2.59022
* lasso.csv -Used lasso model -0.11919
* xg.csv - Xgboost aalgorithm - 0.12370

## Acknowledgments

The Ames Housing dataset used here was compiled by Dean De Cock for use in data science education.
