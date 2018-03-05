Facebook Recruiting IV: Human or Robot?  https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/data 
In this competition it is necessary to idendify robots bidding in auctions. Three data files are provided on the Kaggle website (not available in this repository): 
1- train.csv: the training set from the bidder dataset 
2- test.csv: the test set from the bidder dataset; no human/robot labels provided, indeed this file contains the bidders to be predicted 
3- bids.csv: the bid dataset 
The problem to address is the detection of robots that plague online auctions and frustrate humans users, which are plummeting. This is a classification problem whose classes are strongly unbalanced (a simple check on data shows 5% of robots on the total). 
Kaggle private score obtained with the random forest algorithm in this notebook: 0.90671.
