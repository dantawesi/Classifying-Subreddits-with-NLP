# Project_3

Problem Statement
- Is there a difference in the type of questions asked towards men and women? Are certain types of questions more likely to be asked in either subreddit?

Scraping Data
- Script to request posts from reddit api

Data Cleaning
- place relevant data into dataframe.
- filter unwanted text with regex
- lemmatize remaining text with spacy

EDA
- Show the most frequent words in each subreddit using wordcloud and bar charts

Creating Models
- Models used: Naive Bayes, Log Regression, Random Forest, AdaBoost, Support Vector Machine
- Tfidf used for all models
- various parameters were run for each model with Gridsearch

Assessing Models
- Accuracy, Recall, Specificity scores
- ROC AUC
- Aggregate score from each model

Identify reasons for misclassification
- wordcloud for misclassified posts

