### This is from OH from 12/12

Change the `max iter` a see if there is a change between results so don't have to run so long

We want the raw test scores per the 5 folds for each of the 3 trials

in the gridsearchcv documentation, it says reporting training scores over folds considerably slows the process
just fyi in case youre in a time crunch. it returns them in the cv.results_ and you have to search for them after converting to df

Adult dataset - columsn with race or gender - transform things to numerical values - 
For categorical data, we only do the numerical encoding when the data is ordinal (low, medium, high). Otherwise, we want to use one-hot encoding

For kNN, we can do a logarithmic step instead of a linear step by 26

For gridsearch use built in metric and that accuracy. The scoring argument 
If scoring=None then the default estimator will be used.
Pass in nothing and get the accuracy.

Don't pass in scoring='accuracy'