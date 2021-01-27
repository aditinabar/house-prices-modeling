# house-prices-modeling
Exploration and modeling to predict house sale prices using a Kaggle dataset

There are two notebooks within this project. One labeled Predicting House Prices, and the other Predicting House Prices - Advanced modeling. The first is a rudimentary introduction to modeling methods, and explores the basic workflow of building an ML model. The second (work in progress) will be an exploration of more advanced techniques, in pursuit of peak model performance.

### Methodology

Split data into Train|Test|Validation
Build model using train and test sets
Assess model performance in comparison with other models, using validation set


### Future to do 

- after training, maybe look at the covariance matrix and see how it compares to the coefficients learned, and see if it makes sense
- track training error and testing error vs alpha, and also when changing the sample size to see if there are any improvements
- generate a covariance matrix by doing M x M^T which results in a square matrix, and then run SVD on that square (see jam board)
- if I need to, test this process on 2 or 3 variables that I can visualize, and plot the errors as I vary alpha etc, and then that'll help to understand what happens
    - several different combinations of variables
    - go back and then build on the full dataset.

