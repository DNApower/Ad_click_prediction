# Ad_click_prediction

In real-time bidding (RTB), accurately predicting whether an ad space is worth to bid is critical. As a result, click prediction systems are essential and widely used for real-time bidding. Since the conversion can be as low as 0.1% - 1%, the model has to balance a very skewed two-class dataset.  

In this project, I present such a model based on logistic regression.  To build this model, I first examined and preprocessed the data by removing attributes that are non-informative or redundant, and retaining or transforming those are relevant.  Next, I split the preprocessed data into training and testing sets.  Then, I iterated through model training on training data set, model cross-validation on testing data set and model parameter tuning to find the best model.  Last, I trained the model on the entire dataset and proposed a model deployment strategy based on maximizing net business profit at different conditions. 
