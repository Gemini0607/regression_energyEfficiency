# Regression_energyEfficiency

1. Data

The data was downloaded from the UCI Machine Learning Repository. You can find the relevant information about the data in the description.txt file.

2.The Approach

We perfrom regression on this multi-class data set. Since it is multi-class, the number of algorithms that can be used are restricted. You can find the list of algorithms that cannot be used for multi-class problems in the attachements.  

3. Technique used

-- Linear regression being the most simplest one, has been used first to discover any useful insight if at all it exists. Though the target variables show some linear relation with respect to each other, the feature variables do not show any such strong relation as revealed by the plot as well as by the linear regressor.
-- Out of the remaining applicable regressors, Tree based regressor performances were the best, that to Decision tree being the best, both simple as well as computationally effective.
-- The above claim is confirmed by the R squared values obtained by the evaluation metrics and cross validation scores.      
