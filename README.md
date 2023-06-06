## Predicting Instagram Likes  


The aim of this project is to predict instagram likes given the 'Followers', 'Caption' and 'Hashtags' as input data. 


This project involves textual data. The basic text preprocessing involves remvoving of url, emoticons, punctuations and digits. The text vectorization is performed using `TF-IDF Vectorizer` from nltk library.


The analysis was done in two different methods. One is by extracting features from the text data. New features, e.g. length of caption, topics in hashtags, polarity of sentiment and idf score for each input data was obtained. Using all these as input data, number of 'Likes' were predicted using different Regression Algorithms.


In other method, the 'HashTags' column was taken as input data. This text data was vectorized using the TF-IDF vectorizer and the vectors were used to build the Regression Model. 


For regression analysis, Linear, Ridge, Lasso, KNN, SVM, Decision Tree and Random Forest regressor algorithms were used. 