# Week 2 Assignment

Random Forest Tree algorithm was implemented on the [same dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/adult/) as in previous week.
Accuracy of Random Forest Tree algorithm is **84,55%** which outperfoms Decision Tree algorithm by about 4%.

The **most importans feature** is `fnlwgt`. Also `education-cat`, `capital-gain`, `hours-per-week` contribute much. The **least important features** `native-country-cat` and `race-cat`.

Analysis of Random Tree estimators shows that 25 estimators is optimum for my dataset. 

|Estimators|Accuracy|Estimators|Accuracy|
|:---:|:-----:|:----:|:---:|
|5  |0.831|25|0.845|
|10 |0.842|30|0.842|
|15 |0.838|40|0.844|
|20 |0.844|50|0.843|