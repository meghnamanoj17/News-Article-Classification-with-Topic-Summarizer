# News-Article-Classification-with-Topic-Summarizer
### CSE4022- Natural Language Processing Project 

---
* The motivation of this project is to help in classifying a news dataset into different categories(business, sports, entertainment, politics, business). All the steps i.e. pre-processing, document indexing, feature selection, and news headlines classification is examined in detail. 
* In addition, stop word filtering using a frequency-based stop words removal approach is also discussed. The news articles are categorized using different models namely random forest, logistic regression, Multinomial Naive Bayes, Decision tree, and KNN. Applying hyperparameter tuning for all models, it can be inferred that logistic regression is the best model with the highest accuracy. Here the precision, recall, F1 score has also been predicted.

* The summarization of topics is implemented using extractive summarization. First, we have summarized the news articles from the dataset and added them to a new column, and printed them. To further explore summarization, we have given random news articles as text and summarized them using the TextRank algorithm with the help of spacy and gensim packages. This way, we were able to successfully classify the news articles from the BBC dataset and got the required summaries with good accuracy and performance. 
