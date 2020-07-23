PROJECT NAME :- Twitter sentiment analysis

ABSTRACT :- It is a Natural Language Processing Problem where Sentiment Analysis is done by Classifying the Positive tweets from negative tweets by machine learning models.
            The objective of this task is to detect hate speech in tweets.In this given training dataset label 1 indicates the hate speech and label 0 indicates not a hate speech,
            so finally objective is to predict the labels of test dataset.
            
PROCEDURE :- Firstly both the training and testing dataset had been downloaded from kaggle.
             Checked out the positive and negative tweet, with help of labels from training dataset.
             removed unwanted patterns from the dataset.
             Splitted the training data into train and valid sets from sklearn.
             calculate the f1-score and confusion matrix by machine learning models like random forest classifier and logistic regression.
             
RESULT :-  By Random forest classifier,
           
           Training Accuracy : 0.9946602144257645
           Validation Accuracy : 0.9501939682142411
           F1 score : 0.6004016064257027
           Confusion matrix : [[7294  138]
                              [ 260  299]]
                   
           By logistic regression:
           
           Training Accuracy : 0.984773267698469
           Validation Accuracy : 0.9410586910274058
           f1 score : 0.5915004336513443
           Confusion mtrix :-[[7179  253]
                             [ 218  341]]
