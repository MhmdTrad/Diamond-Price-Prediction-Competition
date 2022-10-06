# Diamond-Price-Prediction-Competition
I was pleased to participate in the first competition on Kaggle, with SHAI For AI | شاي للذكاء الاصطناعي. My team partner Bashar and I worked on analyzing the data and building an accurate diamond price prediction model.

The first step of our project is Exploratory Data Analysis. This step included:  deeply understanding the dataset, then exploring missing data, outliers, and correlations between features, in addition to drawing plots for more analysis.

The second step was model building. In this step, we worked on encoding categorical features, rescaling the features and the target, and splitting data. 
Then we used multiple models to reach the best model that gives us the best performance and accuracy. Some of the models we used like Linear regression, Decision tree, KNeighbors..etc. After many training iterations using the models, we reached out to the top two: Randomforest and Xgboost. After fine-tuning hyperparameters for these models using a randomized search technique, we found the best model with great values for hyperparameters: Xgboost.

Finally, the result of RMSE on testing data is 476.01517.
