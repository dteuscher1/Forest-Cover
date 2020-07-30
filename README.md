# Forest-Cover

This repository shows work done to analyze forest cover data from the Forest Cover Type Prediction Kaggle competition (https://www.kaggle.com/c/forest-cover-type-prediction/overview). 

The study area is four wilderness areas from Roosevelt National Forest in Colorado.  These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices. The data can be obtained from the UCI machine learning respository (https://archive.ics.uci.edu/ml/datasets/Covertype). This data was not used for the project because it includes the cover type for the test set as well. The data used for the analysis and development of the model can from the training set that can be downloaded from the Kaggle website. 

The goal of this competition is to predict the forest cover type (the predominant kind of tree cover) from seven different types of tree cover. As a result, the model will need to predict one out of the 7 groups for each area. The training set includeds 15120 observations with 56 variables. The test set is a lot larger than the training set, which means there may be a problem with overfitting. The test set has 565892 observations with 55 variables.

There are some exploratory plots and analysis done, but this data set had no missing values and only about 54 predictor variables, so there wasn't a lot of preprocessing to be done. Four or five different models were attempted to see the different performance, but the random forest, using the `ranger` through the `caret` package in R, by far performed the best with an accuracy of 76.207%. The competition has already been completed, but based off of the leaderboard results when the competition ended, the results would be in the 69th percentile or the top 31% of participants. 

If there are any questions or comments about the analysis and work done, feel free to email me at david.teuscher.96@gmail.com

