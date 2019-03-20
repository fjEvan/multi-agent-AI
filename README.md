# multi-agent-AI
A multi-agent artificial intelligence project using machine learning techniques and game theroy

Training and tuning a model to predict the probability of an Ad being clicked. 
Develop online bidding algos to bid and get as many impressions and clicks as possible.   

Dataset: online Ads data, a .csv file
Columns include: click,	weekday, hour, bidid, userid, useragent, IP, region, city, adexchange,	domain,	url, urlid, slotid,	slotwidth, slotheight,	slotvisibility,	slotformat,	slotprice, creative, bidprice, payprice, keypage, advertiser, usertag

Input: processed features  
Label: clicked(1) or not(0)
Model output: the probability of each impression(each row) being clicked (from 0 to 1)
Model: Logistic Regression, XGBoost.  
Bidding strategies: Constant bidding, Random bidding, Multi-agent random bidding, Linear Bidding, Polynomial bidding(Quadratic, Cubical, Quartic), Exponential bidding, ORTB strategy, Multi-agent Game theory based strategy

Evaluation: ROC AUC scores and curves

Achievement: 
  grid search performed for parameters, optimal model achieved.
  top on leaderboard
