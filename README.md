## Predicting Instagram Likes  


The aim of this project is to predict instagram likes given the 'Followers', 'Caption' and 'Hashtags' as input data. 

This project involves textual data. The basic text preprocessing involves remvoving of url, emoticons, punctuations and digits. The text vectorization is performed using `TF-IDF Vectorizer` from nltk library.

In this project we have tried to do feature extraction from the given text data. As a starting point the 'Hashtags' column was used for the feature extraction. New features, e.g. length of caption, topics in hashtags, polarity of sentiment and idf score for each input data was obtained. Using all these as input data, number of 'Likes' were predicted using different Regression Algorithms. 

For regression analysis, Linear, Ridge, Lasso, KNN, SVM, Decision Tree and Random Forest regressor algorithms were used. 

