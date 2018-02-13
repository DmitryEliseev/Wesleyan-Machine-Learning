# Week 3 Assignment

Lasso Regression algorithm was implemented on the [same dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/adult/) as in previous week. Predicted variable is age. 

Very import step was to realise One Hot Encoding for categorical variables. This increased MSE by 40 and $R^2$ by 0.25. 

Final model on test sample shows MSE = 108.7 и $R^2$ = 0.42. Such value of $R^2$ can be explained by lack of attributes which really affects `age`. In fact not most of the features, namely `education`, `occupation`,  `race`, `sex`, `hours-per-week`, `native-country`, does not reflect age of person. Consequently, predicting age on this dataset is difficult.

