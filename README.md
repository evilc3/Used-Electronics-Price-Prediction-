![alt text](https://github.com/evilc3/Used-Electronics-Price-Prediction-/blob/master/Screenshot_2020-06-08%20Used%20Electronics%20Price%20Prediction%20Weekend%20Hackathon%20%237%20-%20MachineHack.png)


# Used-Electronics-Price-Prediction-
Given are 6 distinguishing factors that can influence the price of a used device. Your objective as a data scientist is to build a machine learning model that can predict the price of used electronic devices based on the given factors.

# LeaderBoard 
Final position 21 outof 117 participations 

Out in the 18% percentile.

![alt text](https://github.com/evilc3/Used-Electronics-Price-Prediction-/blob/master/leaderboard.png)

# All the Eda and Model Selection Part Can Be Found in the EDA jupyter notebook

 My Final Thoughts : The Provided Dataset lacked any usefull features (at least one that could directly be used). The only way to get a high score was to do heavy feature extraction montly using python regex.That being said The most useful Features were the Model_Info and Location , Brand.

But the Model_Info Cannot be used directly so i had to extract the phone names for each brand. The thing that made it even more difficult was that the company and phone names were encoded (repalced by name_some_number). 

The model I have used was A simple RandomForest Regressor with kfold = 10

I have also used VoterRegressor with RandomForest + ExtraTrees Classifier + KFold = 10

I had tried Xgboost but that produced -ve results.

Some Participatans have used LGB , BERT models will need to look into this later specially at Bert.

# New Things Learned.
The loss function rmsle => root mean squre log error was new to me.
https://medium.com/analytics-vidhya/root-mean-square-log-error-rmse-vs-rmlse-935c6cc1802a



