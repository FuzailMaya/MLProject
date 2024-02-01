# MLProject

SPAM vs NON-SPAM EMAILS

For solving the problem of Classifying mails as spam or not spam, i implemented a Logistic Regression Machine Learning Supervised Model in python which does binary classification of the instance into either of two classes.
The code uses the vectorized implementation using the numpy library which does parallel computing for the calculations in the code, this makes the code run immensely faster than the normal looping implementation. The dataset i used for training the model was taken from UCI Machine Learning Repositry named as Spambase. I divided the data into train and test splits with an 80 to 20 ratio respectively, doing this helped me in testing the trained model on unseen data showing the trained model's Performance. The model accurately predicted emails [data related to emails] as spam or non-spam 91 percent of the unseen data using the trained model.
