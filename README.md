# Hackathon-1
Data preprocessing is done by applying one hot encoding to categorical column and adding some features to capture some underlying patterns.
Training data is divided into training and validation set, then K fold cross validation is applied on each of the below mentioned model, while fitting the model on Training data. 
prediction on the Validation Data is done using multiple methods like Linear regression, Decision tree regression, Support vector regression, Random forest regression and Ridge regression.
Ridge regression is helping here to reduce overfitting and improving RMSE.
At last, Ensembling is used to predict on Test data.
