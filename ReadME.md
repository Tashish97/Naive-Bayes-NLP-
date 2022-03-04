# Naive Bayes
This is a project done using Naive Bayes Classifier to filter/detect spam mails.  
Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature. For example, a fruit may be considered to be an apple if it is red, round, and about 3 inches in diameter. It's based on bayes theorem.  

## Work Done:  
1. Cleaned the text:  
1.1 Removed the Punctuations using regex.  
1.2 Removed the stop words.  
1.3 Rooted the words using lemmatization.  
2. Converted the text data to both bag of words data and tfidf data.  
3. Done hyperparameter tuning using GridSearchCv for both bow and tfidf data.  
4. Confusion matrix and ROC-AUC curve for validation.  
