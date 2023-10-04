# Sentece to Sentence Similarity
## NLP project for text analysis and calssification
* This project aims to develop a classifier to determine whether two sentences are similar or duplicated. By leveraging Natural Language Processing (NLP) techniques, we can preprocess and analyze textual data to identify similarities between sentences
### text preprossing
1.	Text Preprocessing:
a. Convert all words to lowercase.
b. Remove stopwords (commonly occurring words with little semantic value).
c. Eliminate punctuation marks.
d. Remove emojis.
e. Remove non-text elements like URLs or special characters.
2.	Model Preparation:
a. Apply the Counter Vectorizer model to convert preprocessed text into numerical representations.
b. Create vectors based on word frequencies.
3.	Machine Learning Classification:
a. Utilize various ML models (e.g., Random Forest, SVM, Naive Bayes) to classify sentence similarity.
b. Train the models on the preprocessed and vectorized data.
c. Evaluate model performance using appropriate metrics.
4.	Hyperparameter Optimization:
a. Use grid search (GridSearchCV) to find the best ML model and optimal hyperparameters.
b. Select the model with the highest performance.
5.	Deep Learning Classification:
a. Employ deep learning techniques like RNNs or Transformer-based models (BERT).
b. Train the deep learning model on the preprocessed and vectorized data.
c. Evaluate the model's performance using appropriate metrics.

## models 
* Applay the counter vectorizer model to convert the text to numbers 
* apllay the ML models to classifier tge  text id dublicated or not 
* use gradSarchCV to get best mdoel with best prams 
* using deep learning to classifire 
## the accuricy 98 without over fit
### Link of data 
[This is a linle of data](https://www.kaggle.com/code/akshat4112/quora-question-pair-similarity-part-1-basic-eda/data)
